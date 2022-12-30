# Transaction

데이터는 commit되거나, rollback되거나!

<br>
<br>
<br>

## 원자성 (Atomicity)

commit되거나 rollback..abort.. 되거나!<br>
말그대로 atomicity
<br>
<br>

## 일관성 (Consistency)

*흔한 정의보다는 내가 들은 설명을 적겠다.<br><br>*
블록체인은 일관성이 없지만 DB는 일관성이 있다.<br>
>ex) 이더리움이 50000개의 노드에 새로운 block을 완전히 업데이트하는데 12.5초가 걸린다고 하자 => 그러면 6초정도 지난 상황에서는 데이터의 일관성이 없다. (그래서 이때 선택하는 전략이 있다고 함)<br>
블록체인과 달리 DB는 일관성이 달성되어야 한다.

<br>
<br>

## 격리성 (Isolation)

트랜잭션의 격리수준을 이해하자. (isolation level)<br>
 - Serializable     : 
        
        혼란스럽지 않게 단순히 동시처리하지 않음
 - read uncommitted : 
 
        커밋안해도 read가능
 - read committed   : 
 
        커밋된 것만 read
 - repeatable read  :

        백업되는동안 커밋이 여러번 되더라도, 백업전후 커밋상태만 read가능한 거지 백업 도중의 commit된 값들은  필요 없음


ex) <br>
oracle은 read commited의 격리성을 가지고,<br>
mysql은 repeated 수준의 격리성을 가진다.<br>

<br>
<br>

## 지속성 (Durability)

성공적으로 commit된 데이터는 보존되어야 한다는 것