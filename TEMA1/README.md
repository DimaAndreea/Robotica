# TEMA 1: EV Charger

<details>
  <summary> <b> Despre </b> </summary>

  ## Descrierea temei:
   - Aceasta tema simuleaza o statie de incarcare pentru un vehicul electric. Circuitul implementat foloseste mai multe LED-uri si butoane.
   - Circuitul contine un LED RGB ce reprezinta disponibilitatea statiei (verde - disponibil; rosu - incarcarea e activa)
   - De asemenea nivelul de incarcare al bateriei este reprezentat de 4 LED-uri:
     - primul LED -> 25%
     - al doilea LED -> 50%
     - al treilea LED -> 75%
     - al patrulea LED -> 100%
  
   - Incarcarea incepe prin apasarea butonului de START (apasarea acestui buton in timpul incarcarii nu face nimic)
   - Primul LED clipeste de 2 ori, iar a treia oara ramane aprins, cand in acelasi timp se trece la urmatorul LED care incepe si el sa clipeasca. Acest proces continua pana cand se ajunge la ultimul LED, care clipeste de 2 ori si se stinge
   - Fiecare LED clipeste timp de 3 secunde
   - Cand incarcarea a ajuns la final toate cele 4 LED-uri clipesc de 3 ori simultan, iar LED-ul RGB isi schimba inapoi culoarea din rosu in verde
   - Apasarea lunga a butonului de STOP (minim o secunda) opreste fortat procesul de incarcare prin animatia de la final (toate LED-urile clipesc de 3 ori simultan)
##
</details>


<details> 
  <summary><b>Componente</b></summary>
  
  ## Componentele folosite:
  - 4x LED-uri (pentru a simula procentul de încărcare)
  - 1x LED RGB (pentru starea de liber sau ocupat)
  - 2x Butoane (pentru start încărcare și stop încărcare)
  - 9x Rezistoare (7x 220ohm, 2x 1K)
  - Breadboard
  - Linii de legătură
    ##
</details>


<details>
  <summary> <b> Schema electrica </b> </summary>

  ## Schema electrica a circuitului implementat pe Tinkercad
  ![Mighty Kup-Curcan](https://github.com/user-attachments/assets/4649d0a3-51a5-43db-80a4-421e06e5231b)
  ##
</details>


<details>
  <summary> <b> Poze ale setup-ului fizic </b> </summary>
  
  ## Poze cu montajul implementat fizic:
  
![2](https://github.com/user-attachments/assets/57d52a8a-8b1a-4fb2-85a3-e7bd840ff5e4)
![1](https://github.com/user-attachments/assets/9ac6d843-cf6b-4d75-a876-5f470fc70938)
![5](https://github.com/user-attachments/assets/68046be3-143e-4fea-ac2c-671b0a263384)
![4](https://github.com/user-attachments/assets/2e1c19be-fc1a-423d-b72f-714b4565a49d)
![3](https://github.com/user-attachments/assets/e2b85a01-59a3-4292-8514-a3a8adf5d7bf)
##
</details>


<details>
  <summary> <b> Video cu montajul fizic </b> </summary>

  ## Link catre videoul ce arata functionalitatea montajului fizic:
  https://www.youtube.com/watch?v=eAE200TeHGY
  ##
</details>
