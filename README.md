urutanbilanganterkecilketerbesar
================================

#include &lt;stdio.h> #include &lt;conio.h> // urutan tiga bilangan dari kecil ke besar main(){                  int a,b,c;                  printf(" Program Urut Bilangan
");                  printf("
");                  printf("Masukkan bilangan a: ");                  scanf("%i",&amp;a);                  printf("Masukkan bilangan b: ");                  scanf("%i",&amp;b);                  printf("Masukkan bilangan c: ");                  scanf("%i",&amp;c);                  if (a&lt;b &amp;&amp; b&lt;c){                  printf("Urutan bilangan: %i %i %i
",a,b,c);                  }                  else if (a&lt;c &amp;&amp; c&lt;b){                              printf("Urutan bilangan: %i %i %i
",a,c,b);                  }                  else if (b&lt;a &amp;&amp; a&lt;c){                              printf("Urutan bilangan: %i %i %i
",b,a,c);                  }                  else if (b&lt;c &amp;&amp; c&lt;a){                              printf("Urutan bilangan: %i %i %i
",b,c,a);                  }                  else if (c&lt;a &amp;&amp; a&lt;b){                              printf("Urutan bilangan: %i %i %i
",c,a,b);                  }                  else if (c&lt;b &amp;&amp; b&lt;a){                              printf("Urutan bilangan: %i %i %i
",c,b,a);                  }                  return 0 ; }
