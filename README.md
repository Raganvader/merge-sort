# merge-sort

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

----------------CEVAP----------------------
[16,21,11,8,12,22] ilk olarak parçalıyoruz.
[16,21,11] [8,12,22]  parçalamaya devam..
[16]     [21,11]    [8]     [12,22]        parçalamaya devam..
[16]     [21]    [11]  [8]   [12]    [22]   şimdi toplayıp küçükleri sola atmaya çalışıcaz.
[16]     [11,21]       [8,12]     [22] toplamaya devam
[11,16,21]     [8,12,22]  toplamaya devam
[8,11,12,16,21,22] artık hepsi küçükten büyüğe :)


Big-O gösterimi:   O(nlogn) ==- O(6*log6)




