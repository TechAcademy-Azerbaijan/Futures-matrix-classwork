# Matrix 🧠

## Task 1 🎯

### Massivin elementlərinin özündən başqa hasili
n tam ədəd ehtiva edən in massivi verilir. Elə out massivi qurun ki, outiin massivinin ini-dən başqa bütün elementlərinin hasilinə bərabər olsun. Məsələni O(n) və yaddaşa görə sabit mürəkəblikdə həll edin.

### Input
İlk sətir n (1 < n ≤ 10**6) tam ədədini ehtiva edir. İkinci sətir hər biri modulca 100-ü aşmayan n sayda tam ədəd ehtiva edir.

### Output
out massivini verin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    4
    
    1 2 3 4

#### Output example 1

    24 12 8 6
    
    
#### Input example 2

    4
    
    2 0 1 4


#### Output example 2

    0 8 0 0
    
    
#### Input example 3

    10
    
    -3 2 1 -1 1 -2 1 -1 1 -1


#### Output example 3

     4 -6 -12 12 -12 6 -12 12 -12 12

---

## Task 2 🎯

### İki massiv

İki massiv verilib. Birinci massivin o elementlərini çap edin ki, qiymətləri ikinci massivdə olmasın (elementlərin ardıcıllığı birinci massivdəki kimi çap edilməlidir).


### Input
Əvvəlcə birinci massivin elementlərinin n sayı və massivin elelemntləri verilir. Sonra ikinci massivin elementlərinin m sayı və elementləri verilir. Hər iki massivin elementlərinin sayı 100-ü aşmır. Bütün elelmentlər tam ədədlərdir.

### Output
İlk sətirdə cari elementlərin sayını, ikinci sətirdə isə birinci massivin ikinci massivdə olmayan elementlərini verilmiş ardıcıllıqda çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    7
    
    3 1 3 4 2 4 12
    
    6
    
    4 15 43 1 15 1


#### Output example 1

      4  
      
      3 3 2 12

---

## Task 3 🎯

### Müxtəlif elementlərin sayı

N sayda tam ədədlərdən ibarət massivdəki müxtəlif elementlərin sayını tapmaq lazımdır.

### Input
Birinci sətirdə N ədədi verilir. Növbəti sətirdə isə N sayda tam ədəd verilir. Bütün ədədlər modulca 2000 -dən böyük deyil.

### Output
Massivdəki müxtəlif elementlərin sayı.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    7
    
    3 5 -7 7 5 -9 -4
    
#### Output example 1

      6
---

## Task 4 🎯

### Unique elements

Array of n integers is given. Print those elements that appears in array only once. Print the elements in the same order as they appear in the list.

### Input
First line contains number n. Next line contains n integers. All numbers do not exceed 100 by absolute value.

### Output
Print the list of unique elements.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    7
    
    3 5 -7 7 5 -9 -4
    
#### Output example 1

    3 -7 7 -9 -4 
---

## Task 5 🎯

### Matrisdə müsbətlərin cəmi

n * n ölçülü matris verilmişdir. Onun müsbət elementlərinin cəmini tapın.

### Input
İlk sətirdə n (1 ≤ n ≤ 100) ədədi verilir. Növbəti sətirlərdə n * n olçülü matrisin elementləri verilir. Matrisin elementləri modulca 100-ü aşmır.

### Output
Matrisdəki müsbət elementlərin cəmini çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    3
    
    4 -2 5
    1 -4 -12
    0 1 -3

    
#### Output example 1

    1
---

## Task 6 🎯

### Diaqonallar

n × n ölçülü kvadrat cədvəldə əsas və tərs diaqonallarda yerləşən ədədlərin cəmini hesablayın.

### Input
Əvvəlcə n (1 ≤ n ≤ 500) ədədi, sonra isə n × n matrisi daxil edilir. Matrisin elementləri modulca 10**5-i aşmır.

Hansı dioqanalın necə adlandırıldığını başa düşmək üçün ikinci nümunə testə diqqətlə baxın.

### Output
Əvvəlcə əsas diaqonalın, sonra isə tərs diaqonalın elementlərinin cəmini çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

      4
      
      134 475 30 424
      303 151 419 235
      248 166 90 42
      318 237 184 36


    
#### Output example 1

    411 1327
---

## Task 7 🎯

### Cross
Nümunəyə baxın...

### Input
Bir tam ədəd n (1 ≤ n ≤ 50).

### Output
Nümunəyə baxın...

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1

    3

#### Output example 1

    *   *
     * *
      *
     * *
    *   *



#### Input example 2

    5

#### Output example 2

    *       *
     *     *
      *   *
       * *
        *
       * *
      *   *
     *     *
    *       *


---


## Task 8 🎯

### Teatrın mədaxili

Teatrda hər birində M yer olan N sıra var. İki matris verilir – birincidə biletlərin sayı. İkinci isə hansı biletlərin satıldığını, hansıların satılmadığını bildirir (1 – uyğun biletin satıldığını, 0 isə satılmadığını).

Tamaşadan əldə olunan ümumi mədaxili təyin edin.


### Input
Giriş faylında əvvəlcə N ədədi, daha sonra M ədədi verilir. Sonra isə biletlərin qiymətləri matrisi verilir (Hər birində M ədəd olan N sətir, hər bir ədəd 0-dan 10000-ə qədərdir). Sonra satılan biletlər matrisi verilir (yenə də hər birində M ədəd olan N sətir. N, M ≤ 500).
Hansı dioqanalın necə adlandırıldığını başa düşmək üçün ikinci nümunə testə diqqətlə baxın.

### Output
Çıxış faylına bilet satışından əldə olunan ümumi mədaxili verin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    3 3
      
    1 2 3
    4 5 6
    7 8 9

    1 0 1
    0 1 0
    1 0 1



    
#### Output example 1

    25
    
---
