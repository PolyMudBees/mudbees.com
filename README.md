# Site web du baja
Le site web promotionnel du baja qui permet aux gens de savoir en quoi consiste le baja.
## Publication
La publication s'effectue automatiquement quand un `tags` qui correspond au pattern `*-release`. C'est un `tag` protégé, donc seulement les maintainers devraient être capables de push ces `tags`. Voir le [guide des contributions](CONTRIBUTING.md).
### Publication manuelle
Première fois (dans le folder qui vous tente):
```bash
git clone https://gitlab.baja.polymtl.ca/tlaferriere/mudbees-com.git
cd mudbees-com
chmod u+x update.sh
sudo ./update.sh
```
Après ça:
```bash
cd mudbees-com
git pull
sudo ./update.sh
```