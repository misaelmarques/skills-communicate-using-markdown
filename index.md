## de novo

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

![NOVA IMAGEM ALEATÓRIA](https://picsum.photos/200/300)

``` python
def menu_usuario():
    print("Escolha o modelo de recibo:")
    print("1. Modelo Masculino")
    print("2. Modelo Feminino")
    escolha = input("Digite o número da opção desejada: ")

    diretorio_base = os.path.dirname(os.path.abspath(__file__))
    pasta_modelos = os.path.join(diretorio_base)

    if escolha == '1':
        return os.path.join(pasta_modelos, 'MODELO_RECIBO_MASCULINO.docx')
    elif escolha == '2':
        return os.path.join(pasta_modelos, 'MODELO_RECIBO_FEMININO.docx')
    else:
        print("Opção inválida. Por favor, escolha 1 ou 2.")
        return menu_usuario()  # Chama a função novamente até uma opção válida ser escolhida
```

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
