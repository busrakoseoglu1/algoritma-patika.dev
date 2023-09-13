# algoritma-patika.dev
 

<h2>Soru 1 - Selection Sort Projesi</h2> 

<p>[22,27,16,2,18,6] -> Insertion Sort 

  

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 

  

Big-O gösterimini yazınız. 

  

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız 

  

Average case: Aradığımız sayının ortada olması 

Worst case: Aradığımız sayının sonda olması 

Best case: Aradığımız sayının dizinin en başında olması. 

. 

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.</p> 

<h1>Insertion Sort</h1> 

<p>Verilen dizi [22, 27, 16, 2, 18, 6] için Insertion Sort adımları:</p> 

<ol> 

  <li>[<b>22</b>, 27, 16, 2, 18, 6]</li> 

  <li>[<b>22, 27,</b> 16, 2, 18, 6]</li> 

  <li>[16,<b> 22, 27</b>, 2, 18, 6]</li> 

  <li>[<b>2,</b> 16, 22, 27, 18, 6]</li> 

  <li>[2, <b>16,</b> 22, 27, 18, 6]</li> 

  <li>[2, 16, <b>18</b>, 22, 27, 6]</li> 

  <li>[<b>2, 6,</b> 16, 18, 22, 27]</li> 

  </ol> 

  <br> 

  <br> 

<h1>Big-O Gösterimi</h1> 

<p> 

  N elemanlı bir diziyi sıralamak için: 

  

1 + 2 + ... + (n-1) + n 

  

= (n * (n+1)) / 2 

  

= (n² + n) / 2 

  

= O(n²) 

</p> 

  <h1>Time Complexity</h1> 

  <p>Average case: Aradığımız sayının ortada olması</p> 

  <br><br> 

  <h1>[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisi için Selection Sort:</h1> 

  <p>Selection Sort adımları (ilk 4 adım):</p> 

  <ol> 

    <li>[2, 3, 5, 8, 7, 9, 4, 15, 6]</li> 

    <li>[2, 3, 5, 8, 7, 9, 4, 15, 6]</li> 

    <li>[2, 3, 4, 8, 7, 9, 5, 15, 6]</li> 

    <li>[2, 3, 4, 5, 7, 9, 8, 15, 6]</li> 

  </ol> 

  

  <hr> 

  <h1>Soru 2 - Merge Sort Projesi</h1> 

  <p>[16,21,11,8,12,22] -> Merge Sort 

  

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 

Big-O gösterimini yazınız.</p> 

<ol> 

  <li>Diziyi ortadan ikiye böleriz.<br>[16, 21, 11] | [8, 12, 22]</li> 

  <li>Her iki yarı diziyi aynı işlemle tekrar böleriz.<br> 

  <ul> 

    <li>[16] | [21, 11]</li> 

    <li>[16] | [21] | [11]</li> 

    <li>[8, 12] | [22]</li> 

    <li>[8] | [12]</li> 

    <li>[8] | [12, 22]</li> 

  </ul>

  <li>Bölünmüş dizileri sıralı bir şekilde birleştiririz.<br> 

  <ul> 

    <li>[16] | [11, 21]</li> 

    <li>[11, 16, 21]</li> 

    <li>[8] | [12, 22]</li> 

    <li>[8, 12, 22]</li> 

  </ul> 

  </li> 

<li>İki sıralı yarı diziyi birleştirerek sonuç dizisini elde ederiz.<br> 

[11, 16, 21] | [8, 12, 22]<br> 

[8, 11, 12, 16, 21, 22]</li> 

</ol> 

<h1>Big-O Gösterimi</h1> 

<p>Big-O gösterimi O(n * logn)'dir</p> 

<hr> 

<h1>Soru 3 - Binary Search Tree Projesi</h1> 

<p>[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. 

  

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.</p> 

<ol> 

  <li>7 root'tur.</li>  

  <li>5, 7'nin solunda yer alır.</li>  

  <li>1, 7'nin solunda yer alır.</li>  

  <li>8, 7'nin sağındadır.</li>  

  <li>3, 5'in sağındadır.</li>  

  <li>6, 7'nin sağındadır.</li>  

  <li>0, 1'in solunda yer alır.</li>  

  <li>9, 8'in sağındadır.</li>  

  <li>4, 5'in sağındadır.</li>  

  <li>2, 1'in sağındadır.</li>  

</ol> 
