# Clean V4

## DESCRICÃO
#### Pacote de navegação ROS do tipo ponto a ponto, o robô inicia no ponto zero vai para o ponto 1 para coletar carga, aguarda validação de usuário, após validado vai ao ponto 2 para deixar carga e aguarga validação para retornar ao ponto 1 para pegar nova carga.

## PRÉ REQUISITOS

### Geral:
1. SO Ubuntu 20.04

### Pacotes ROS:
1. sudo apt install ros-noetic-move-base
2. sudo apt install ros-noetic-slam-gmapping
3. sudo apt install ros-noetic-amcl
4. sudo apt install ros-noetic-dwa-local-planner
5. sudo apt install ros-noetic-map-server
6. sudo apt install ros-noetic-openzen-sensor
7. sudo apt install ros-noetic-robot-localization
8. sudo apt install ros-noetic-sound-play
9. sudo apt install ros-noetic-teb-local-planner
10. sudo apt install ros-noetic-sick-safetyscanners
11. sudo apt install ros-noetic-laser-scan-matcher


### Node-red Palettes:
1. snappy-ros
2. node-red-contrib-uibuilder
3. node-red-contrib-s7 

### Uibuilder libraries:
1. vue
2. bootstrap
3. bootstrap-vue
4. jquery
5. nipplejs


## RESULTADOS OBTIDOS

https://user-images.githubusercontent.com/68859813/152146520-610094e5-8b47-4d73-bb31-ebf06f708a18.mp4

## NOTA DE ATUALIZAÇÃO

<details><summary>CLEAN V4</summary>
  
<ul>

<li> 
  
<details><summary>Interface de usuário</summary>

<h2>Adição de feedback de status:</h2>
  
 <h3>Mobile</h3>
  
  ![giffycanvas (11)](https://user-images.githubusercontent.com/72092263/151812344-1c309620-8690-4277-a6c7-5f26130f8926.gif)


  Os outros status são:
  
 - ![C4C4C4](https://user-images.githubusercontent.com/72092263/150834277-5256d399-f94d-4965-9480-547421884d6b.png) Ocupado;
     
 - ![00ffff](https://user-images.githubusercontent.com/72092263/150833504-dd91c3ff-37f4-4a44-9e26-a075ee5e61b6.png) Disponível;

 - ![35F950](https://user-images.githubusercontent.com/72092263/150834036-ce34759c-9d25-48e5-b497-03717b1b4faa.png) Modo manual;
  
 - ![7f00ff](https://user-images.githubusercontent.com/72092263/150833241-fb4ccb08-5f72-4519-99b2-5244171cc106.png) Em gravação;
 
 -  ![ff0000](https://user-images.githubusercontent.com/72092263/151424795-dfc533b8-f9f8-4fe0-91da-165cd81e0be8.png) Falha
    
<h3>Tablet</h3>
  
 ![giffycanvas (12)](https://user-images.githubusercontent.com/72092263/151812735-ab02bb28-b934-4dcf-b694-2528a5275034.gif)



  Os outros status são:
  
 - ![C4C4C4](https://user-images.githubusercontent.com/72092263/150834277-5256d399-f94d-4965-9480-547421884d6b.png) Ocupado;
     
 - ![00ffff](https://user-images.githubusercontent.com/72092263/150833504-dd91c3ff-37f4-4a44-9e26-a075ee5e61b6.png) Disponível;

 - ![35F950](https://user-images.githubusercontent.com/72092263/150834036-ce34759c-9d25-48e5-b497-03717b1b4faa.png) Modo manual;
  
 - ![7f00ff](https://user-images.githubusercontent.com/72092263/150833241-fb4ccb08-5f72-4519-99b2-5244171cc106.png) Em gravação;
 
 -  ![ff0000](https://user-images.githubusercontent.com/72092263/151424795-dfc533b8-f9f8-4fe0-91da-165cd81e0be8.png) Falha
    
<h3>Desktop</h3>

![giffycanvas (13)](https://user-images.githubusercontent.com/72092263/151813005-75488d15-40d3-4da2-a29a-5517e2be6b75.gif)


 Os outros status são:
  
 - ![C4C4C4](https://user-images.githubusercontent.com/72092263/150834277-5256d399-f94d-4965-9480-547421884d6b.png) Ocupado;
     
 - ![00ffff](https://user-images.githubusercontent.com/72092263/150833504-dd91c3ff-37f4-4a44-9e26-a075ee5e61b6.png) Disponível;

 - ![35F950](https://user-images.githubusercontent.com/72092263/150834036-ce34759c-9d25-48e5-b497-03717b1b4faa.png) Modo manual;
  
 - ![7f00ff](https://user-images.githubusercontent.com/72092263/150833241-fb4ccb08-5f72-4519-99b2-5244171cc106.png) Em gravação;
 
 -  ![ff0000](https://user-images.githubusercontent.com/72092263/151424795-dfc533b8-f9f8-4fe0-91da-165cd81e0be8.png) Falha

</details>

</li>
 
<li>
  
<details><summary>feedback visual no robô</summary>

https://user-images.githubusercontent.com/68859813/152146520-610094e5-8b47-4d73-bb31-ebf06f708a18.mp4

</details>
 
</li>
  
  
</ul>
  
</details>


<details><summary>CLEAN V3</summary>

<ul>

<li>

<details><summary>Sistema de Localização</summary>

https://user-images.githubusercontent.com/68859813/149972970-f42ed59d-f6f5-49f9-9dc3-771a58d93b06.mp4

</details>

</li>

<li>

<details><summary>Interface de usuário</summary>

<h3>Feedback da porcentagem de bateria nas telas:</h3>

Para Tablet

![tablet - img1](https://user-images.githubusercontent.com/72092263/148820551-7e79415a-0b63-4e5f-af87-8813e91bd90d.png)
![tablet - img2](https://user-images.githubusercontent.com/72092263/148820570-2f07fb66-d089-448e-a5d5-020712a93dfc.png)

Imagem de quando está carregando

![tablet - img3](https://user-images.githubusercontent.com/72092263/148821360-90efb2e3-7dfb-4cb8-aa1c-eec4a4011e37.png)
![tablet - img4](https://user-images.githubusercontent.com/72092263/148822082-a2a671ac-4fde-4f4f-a50e-00d71a9bdb52.png)

Para Mobile

![mobile - img1](https://user-images.githubusercontent.com/72092263/148820652-c4e34186-b667-4262-b939-4293c552ef8a.png)
![mobile - img2](https://user-images.githubusercontent.com/72092263/148820663-39515d4c-083c-41b1-8462-bb2e5d410cfc.png)

Imagem de quando está carregando

![mobile - img3](https://user-images.githubusercontent.com/72092263/148821442-f8d14720-b86a-428f-8a01-82eaeb2b8e96.png)
![mobile - img4](https://user-images.githubusercontent.com/72092263/148822109-6f2b8372-8f51-40c3-9f75-07f575e3e30e.png)

Para Desktop

![desktop - img1](https://user-images.githubusercontent.com/72092263/148820686-4413c2b3-2816-4587-af38-fedf3ef4cf28.png)
![desktop - img2](https://user-images.githubusercontent.com/72092263/148820693-c42bd14e-4e78-48b1-8852-d850618be884.png)

Imagem de quando está carregando

![desktop - img3](https://user-images.githubusercontent.com/72092263/148821490-e0770d3f-0637-4179-b169-e6d1d81f5fa2.png)
![desktop - img4](https://user-images.githubusercontent.com/72092263/148822141-94d1381b-3230-4d3c-bbd2-1eb44ea2c669.png)

</details>

</li> 

</ul>

</details>
<details><summary>CLEAN V2</summary>
  <h3>Responsividade das telas:</h3>

  Para mobile

  ![img3](https://user-images.githubusercontent.com/72092263/147571146-726c12fd-c4a9-4b62-9dfe-4c01abb291d9.png)
  ![img4](https://user-images.githubusercontent.com/72092263/147571149-8c420102-890a-4444-89d2-355197b76a1e.png)

  Para desktop

  ![img2](https://user-images.githubusercontent.com/72092263/147571183-24e4e2df-782b-4e45-84d9-2c2f2f5c48fa.png)
  ![img1](https://user-images.githubusercontent.com/72092263/147571189-95a1730f-5646-4c23-a117-d915e06dc2b0.png)

</details>

<details><summary>CLEAN V1</summary>  
   
  https://user-images.githubusercontent.com/72092263/147564360-5cc03d4c-f313-4f7f-974e-933ab8ebcc57.mp4
 
</details>

## DESENVOLVEDORES
<table> 
  <tr> 
    <td align="center"><a href="https://www.linkedin.com/in/clistenes-bento-28430911b" target="_blank"><img src="https://user-images.githubusercontent.com/68859813/143960838-cdea45a4-ec09-4e60-8852-b3f1a75d9540.png" alt="Cístenes Grizafis Bento"></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/daiana-vaz-torres-28849210a/" target="_blank"><img src="https://user-images.githubusercontent.com/72092263/147569055-49e03c23-b49d-4950-bd80-2047d6ced9b5.png" 
alt="Daiana Vaz Torres"></a></td>
  </tr>  
  <tr> 
    <td align="center">Clístenes Grizafis Bento</td>
    <td align="center">Daiana Vaz Torres</td>
  </tr>
  
  <tr> 
    <td>https://github.com/Hobbies-Prof-Bento</td>
    <td>https://github.com/daianalien</td>
  </tr>
</table>



## Quaisquer dúvidas, sugestões ou atualizações pode ficar a vontade para entrar em contato!!!

@github/Selettra-automacao-e-robotica
https://github.com/Selettra-automacao-e-robotica/Clean
