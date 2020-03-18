#!bin/bash
#create by: Cortez

echo " Esgriba su Alias"

read es

#comenzando

echo  "\e[91mcreate by Cortez para el grupo de Termux\e"



#instalaciones

echo  " $es Hoy  te mostrare el estatus del un  Hots"

 sleep 2

echo "Ingresa tu Hots: "
 read Hots
 sleep 2

 echo "buscando estatatus de $Hots"

pkg install curl

 curl -v $Hots




 #Fin
