# Reconhecimento facial com Python

<pre>
 ____                             _                  _                          _             
|  _ \   ___   ___   ___   _ __  | |__    ___   ___ (_) _ __ ___    ___  _ __  | |_   ___     
| |_) | / _ \ / __| / _ \ | '_ \ | '_ \  / _ \ / __|| || '_ ` _ \  / _ \| '_ \ | __| / _ \    
|  _ < |  __/| (__ | (_) || | | || | | ||  __/| (__ | || | | | | ||  __/| | | || |_ | (_) |   
|_| \_\ \___| \___| \___/ |_| |_||_| |_| \___| \___||_||_| |_| |_| \___||_| |_| \__| \___/    
                                                                                              
 _____               _         _                                ____          _    _                   
|  ___|  __ _   ___ (_)  __ _ | |     ___   ___   _ __ ___     |  _ \  _   _ | |_ | |__    ___   _ __  
| |_    / _` | / __|| | / _` || |    / __| / _ \ | '_ ` _ \    | |_) || | | || __|| '_ \  / _ \ | '_ \ 
|  _|  | (_| || (__ | || (_| || |   | (__ | (_) || | | | | |   |  __/ | |_| || |_ | | | || (_) || | | |
|_|     \__,_| \___||_| \__,_||_|    \___| \___/ |_| |_| |_|   |_|     \__, | \__||_| |_| \___/ |_| |_|
                                                                       |___/                           
</pre>

Veja aqui como reconhecer e manipular faces de forma muito simples com a biblioteca ```face_recognition```, usando o reconhecimento facial de última geração da ```dlib```, com aprendizado profundo.

![Imagem1](https://github.com/lisaterumi/reconhecimento-facial-python/raw/f2fa00f6514e50f540101a0be2959faeed7826ac/img/nova_imagem.jpg)

![Imagem2](https://github.com/lisaterumi/reconhecimento-facial-python/raw/f2fa00f6514e50f540101a0be2959faeed7826ac/img/nova_imagem2.jpg)

Aqui veremos como uma ferramenta simples de linha de comando ```face_recognition``` para o reconhecimento facial com linha de comando. 

### Bibliotecas

Primeiro, instale a biblioteca **face-recognition**:

```pip install face-recognition```

Obs: Caso ocorra erro ao instalar o **dlib**, faça o seguinte:

1. Instale anaconda
2. Execute os comandos no *shell*

```conda update conda```

```conda update anaconda```

```create new environment conda create -n env_dlib python=3.6```

```activate enviroment conda activate env_dlib```

```install dlib conda install -c conda-forge dlib```

3. Verifique a instalação via cmd:

```>> python```

```import dlib```

```dlib.__version__```

[Acesso ao notebook](https://github.com/lisaterumi/reconhecimento-facial-python/blob/main/reconhecimento-facial-python.ipynb).


