# Mi chuleta de git
echo '# Mi chuleta de git' > CHULETA.md   # nuevo: sin seguimiento (rojo)
git add CHULETA.md  # preparado (verde)
git commit -m "Añade una chuleta de git"  # guardado: ya no sale
code CHULETA.md # lo cambias: modificado (rojo)                           
git add CHULETA.md # preparado otra vez (verde)                        


## Ciclo de cada día
git pull # al empezar: trae lo nuevo de GitHub                  
git status # ¿qué ha cambiado?               
git diff # ¿qué he cambiado exactamente?                 
git add CHULETA.md # prepara ese fichero        
git commit -m "Añade..."  # la foto, con un mensaje
git push # súbelo a tu fork                  
git log --oneline # el historial, un commit por línea

## Vuelvo a la practica 1

- `git log--oneline`: el historial, un commit por línea
- `git commit-am "mensaje"`: add y commit de lo ya seguido
- `git restore <fichero>`: descarta lo que no has guardado
- Atajos de teclado: mira ATAJOS.md
