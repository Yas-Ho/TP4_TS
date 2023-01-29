# TP4_TS ___ Filtrage Analogique

# 1)Définir le signal x(t) 

 ![image](https://user-images.githubusercontent.com/97410524/215357830-46924a09-2e55-49e4-91fe-905d05cf7226.png)


# 2)Tracer le signal x(t) avec sa transforme de Fourier

  ![image](https://user-images.githubusercontent.com/97410524/215357851-91850b00-f0d9-471a-8d8d-cf6f9f41a97e.png) ![image](https://user-images.githubusercontent.com/97410524/215357868-f35eb927-e380-45a0-9e1d-d9bc57fa3295.png)


  
on remarque que le premier signal n'est pas précis
 
 ![image](https://user-images.githubusercontent.com/97410524/215357885-ebe100a5-86e6-405a-9be3-e50948608e0e.png)
 ![image](https://user-images.githubusercontent.com/97410524/215357892-03087a2c-33d7-41db-a949-c0d967ad157b.png)

 
on sait que H(f) = (K.j.w/wc) / (1 + j. w/wc)
# 1)Tracer le module de la fonction H(f)
 
 ![image](https://user-images.githubusercontent.com/97410524/215357895-72edfe6b-927a-4ceb-976b-2d284d50f41d.png)
![image](https://user-images.githubusercontent.com/97410524/215357911-f8c65dc6-9b4f-43e1-8449-52777b1ce01b.png)


# 2)Tracer 20.log(|H(f)|) pour différentes pulsations de coupure wc
 
 ![image](https://user-images.githubusercontent.com/97410524/215357920-6e4a0621-208d-4e73-ae87-fc72f487d2ea.png)
![image](https://user-images.githubusercontent.com/97410524/215357929-84bc4815-d843-4fe4-afe9-edb76d32b1e3.png)

 
# 3)on choisit différentes fréquences de coupure

![image](https://user-images.githubusercontent.com/97410524/215357939-70eb6336-30bb-4e99-9bef-b55d0513486b.png)
![image](https://user-images.githubusercontent.com/97410524/215357949-64caecc1-dacb-4fd5-a7c3-025fef320b70.png)

 
 
# 4)Choix de wc optimal
En appliquant la transmittance complexe de fréquence 500 sur le signal, on peut remarquer une réduction de l'amplitude du signal sur toute sa longueur, avec une réduction plus importante dans les fréquences basses.

# 5)on observe le signal y(t)
 ![image](https://user-images.githubusercontent.com/97410524/215357956-52089005-99a1-4026-ba0e-18cd929b2960.png)

Dé-bruitage d'un signal sonore
filtrage

# 2) Mettez-la en oeuvre
 
 ![image](https://user-images.githubusercontent.com/97410524/215357963-dadbdfb3-5feb-4175-93aa-4ca514105d86.png)
 ![image](https://user-images.githubusercontent.com/97410524/215357974-af75b000-2bf2-4aa3-9e66-e1b9f861e623.png)

 
3-un filtre analogique ne permet que de réduire le bruit, et comme nous l'avons vu auparavant, lors de la réduction du bruit dans un autre signal, il n'est pas possible de filtrer le signal avec une transmittance complexe d'ordre 1 sans affecter le signal. Par conséquent, un filtre passe-bas de premier ordre ne sera pas efficace pour éliminer le bruit.

# 4) on ameliore la qualite en augmentant l'ordre
 
![image](https://user-images.githubusercontent.com/97410524/215357981-c8c22ebb-2dae-4bab-b3d1-ca75e79f4b88.png)

