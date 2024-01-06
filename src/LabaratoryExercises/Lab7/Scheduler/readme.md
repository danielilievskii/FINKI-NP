Оваа задача е многу слична како задачата од лабараториска вежба 4 задача број 2 - меѓутоа сега ќе користите мапа за да ја имплементирате класата Sheduler и НЕ ви треба класата Timestamp.

Потсетување за задачата: Да се развие класа Scheduler. Оваа класа чува објекти од генерички тип T кои единствено се референцираат преку време (објект од класата Date). Класата треба да ги имплементира следниве методи:

* Sheduler() - креира нов празен распоредувач
* add(Date d, T t) - додава нов објект во распоредувачот
* remove(Date d):boolean - го брише соодветниот елемент од распоредувачот доколку постои и враќа true, во спротивно враќа false
* next():T - го враќа следниот објект, односно тој објект кој е асоциран со дата најблиска до тековната и сеуште не е помината
* last():T - го враќа следниот објект, односно тој објект кој е асоциран со дата најблиска до тековната и веќе е помината
* getAll(Date begin,Date end):ArrayList<Т> - враќа листа на објекти чии дати се наоѓаат помеѓу begin и end.

Забелешка: Два објекти НЕ може да имаат исто време.

Имплементирајте и два дополнителни методи:

* getFirst():Т - го враќа објектот асоциран со најмала дата (севкупно)
* getLast():Т - го враќа објектот асоциран со најголема дата (севкупно)