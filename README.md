# CollectionFramework_SetInterface
Java - HashSet, LinkedHashSet ve TreeSet


    Set Interface ----> HashSet,LinkedHashSet, TreeSet

    Set Interface ile List Interface’in farkı
    List interface’i implemente eden classlar bir elementten birden fazla depolayabilirken,  
    Set interface’i implemente eden classlar bir elementten sadece bir tane depolarlar.

    HashSet Sınıfı

    HashSet extends AbstractSet implements Set Interface extends Collection extends Iterable

    1.HashSet elementleri "hashing" yani hash table  mekanizmasına uygun bir biçimde depolarlar
    (Her element belli bir key'e göre depolanır.)

    2.HashSet bir element'i sadece bir defa depolar.(Set Interface)

    3. Elementlerin ekleme sırasına göre depolamaz.

    LinkedHashSet Sınıfı

    LinkedHashSet extends HashSet extends AbstractSet implements Set Interface extends Collection extends Iterable

    1. LinkedHashSet hem HashTable hem de Set Interface'in LinkedList implementasyonu gibi davranır.

    2. HashSette olduğu gibi bir elementi sadece bir defa depolar.(Set Interface)

    3. Elementleri ekleme sırasına göre depolar.


    TreeSet Sınıfı

    TreeSet sınıfı NavigableSet inteface'ini implemente eder ve AbstractSet sınıfından miras alır. 
    NavigableSet interface'i de SortedSet interfaceinden miras alır. 

    1. Elementleri depolamak için Tree yani Ağaç yapısını kullanır.

    2. Elementleri alfabetik olarak sıralarlar.



    HashSet vs LinkedHashSet vs TreeSet

    HashSet, Hash Table mekanizmasını uyguladığı için elementler sıralı değildir. Ekleme,Çıkarma ve
    Arama metodları sabit zamanda( Time Complexity : O(1) ) çalışır. 

    TreeSet, elementleri tree yapısına yani ağaç yapısına uygun depolar. Ekleme,Çıkarma ve 
    Arama metodları O(log(n)) complexitysi ile çalışır.

    LinkedHashSet sınıfı hashtable ile linked list yapısını kullanarak elementleri depolar.Bu yüzden,
    elemetler ekleme sırasına göre depolanır. Ekleme,Çıkarma ve Arama metodları 
    sabit zamanda( Time Complexity : O(1) ) çalışır.
