Patika Profil Linki
`https://app.patika.dev/yigitcanga`

# Merge Sort

Merge Sort mekanizması aşağıdaki şekilde çalışmaktadır.

Merge sort’ta ana mantık küçük problemleri çözerek bütüne bağlamaktır. Problem küçük parçalara bölünür. Daha küçük parçalara bölünen problemler çözülür. Çözülmüş küçük parçalar tekrar birleştirilir.

[16,21,11,8,12,22] dizisi bu işlemlere göre aşağıdaki gibi sıralanır.

1. Dizi [16,21,11] , [8,12,22] dizileri olarak ikiye bölünür.
2. Soldaki dizi 16 ve [21,11] olarak bölünür ve bu diziler kendi içinde sıralanarak 16 ve [11,21] elde edilir. Bu iki dizi birleştirilerek [11,16,21] elde edilir.
3. Sağdaki dizi 2 ve [12,22] olarak bölünür ve bu diziler kendi içinde sıralanarak 8 ve [12,22] elde edilir. Bu iki dizi birleştirilerek [8,12,22] elde edilir.
4. En son elde edilen iki dizi birleştirilerek [8,11,12,16,21,22] dizisi elde edilir.
5. Dizinin Big O notation gösterimi O(n*logn) dir
