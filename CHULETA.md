# Mi chuleta de git
echo '# Mi chuleta de git' > CHULETA.md   # nuevo: sin seguimiento (rojo)
git add CHULETA.md                        
# preparado (verde)
git commit -m "Añade una chuleta de git"  # guardado: ya no sale
code CHULETA.md                           
git add CHULETA.md                        
# lo cambias: modificado (rojo)
# preparado otra vez (verde)