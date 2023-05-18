# commit-testing

Primer commit como el usuario loggeado

`git commit -m "felipe hizo commit aquí"`


Segundo commit con otro usuario

`git commit --author="Diego Millan <diego.millan@edunext.co>"`


Tercer commit copiando el metadata de un commit anterior

`git commit -c bc09131b418167ba8d0f0c27398a35c88b6bd208`

Cuarto commit hecho por fmo con signature

`git config --global commit.gpgsign true`
