# guake-preferences
Minhas preferências para usar o guake terminal

<details>
	<summary>Demo</summary>
	![demo](/src/demo.png)
</details>


### Instalação

##### APT
	apt install guake

##### Python3
	pip3 install --user guake

##### Source (guake v3.8.0.0rc2)
	git clone https://github.com/Guake/guake/
	cd guake

	# listar tags $ git tag -l
	git checkout tags/3.8.0.0rc2

	make
	sudo make install

[Mais informações](https://guake.readthedocs.io/en/stable/user/installing.html)


### Carregar Preferências
	git clone --depth 1 https://github.com/brunodavi/guake-preferences
	cd guake-preferences
	guake --restore-preferences=my-preferences
