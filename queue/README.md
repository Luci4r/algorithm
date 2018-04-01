О́чередь — абстрактный тип данных с дисциплиной доступа к элементам «первый пришёл — первый вышел» (FIFO, англ. first in, first out). Добавление элемента (принято обозначать словом enqueue — поставить в очередь) возможно лишь в конец очереди, выборка — только из начала очереди (что принято называть словом dequeue — убрать из очереди), при этом выбранный элемент из очереди удаляется. 

![IMAGE](/img/Queue.png)

Queue ADT Operations:  
* Enqueue(): Добавить новый элемент в конец очереди.
* Dequeue(): Удаление элемента из передней части очереди и возврат его значения.
* Peek(): Вернуть значение элемента в начале очереди.
* Len(): Возвращает количество элементов внутри очереди.