# 연결 리스트 (LinkedList)

## 단순 연결 리스트 (Singly Linked List)
* 단순 연결 리스트는 노드에 다음 노드의 주소를 가리키는 정보만 추가되어 있는 가장 단순한 형태의 연결 리스트입니다.
* 가장 마지막 원소를 찾으려면 처음부터 리스트 끝까지 탐색해야 하기 때문에 시간 복잡도가 O(n)입니다.
* 이 자료구조는 가장 첫번째 노드의 참조 주소를 잃어버릴 경우 데이터 전체를 사용하지 못하는 단점이 있습니다.
* 또한, 다음 노드를 참조하는 주소 중 하나가 잘못되는 경우에도 리스트가 끊어져 그 이후 자료들을 유실할 수 있는 불안정한 자료구조입니다.

## 이중 연결 리스트 (Doubly Linked List)
* 다음 노드의 참조와 이전 노드의 참조도 같이 가리키게 하는 자료구조입니다.
* 단순 연결 리스트와 다르게 뒤에서부터 탐색하는 것이 빠르며, 특정 노드를 삭제하는 것을 간단하게 구현할 수 있습니다.
* 또한, 첫 노드와 마지막 노드 중 하나를 가지고 있다면 전체 리스트를 순회할 수 있기 때문에 끊어진 리스트를 복구할 수 있습니다.
* 하지만, 관리해야 하는 참조 주소가 2개로 삽입이나 정렬의 경우 작업량이 더 많고 소모되는 메모리도 더 많습니다.

## 원형 연결 리스트 (Circular Linked List)
* 단순 연결 리스트에서 마지막 원소를 null이 아닌 첫 노드의 주소를 가리키게 하면 원형 연결 리스트 자료구조가 됩니다.
* 이 방법은 이중 연결 리스트에도 동일하게 적용됩니다.