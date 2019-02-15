# Pressao - Controle de Pressão Arterial
*Registre*, *Visualize*, *Procure* todos seus registros de pressão arterial com o Pressão.<br/><br/>

**Coloque em /usr/local/bin e dê permissão de execução!**

> ### Imagens:
> Opção '**inserir**' para inserir novo registro:<br/>
> ![](https://notabug.org/jeffersonrocha/Pressao/raw/master/img/1.png)<br/><br/><br/>
> Opção '**visualizar**' visualize todo banco de dados:<br/>
> ![](https://notabug.org/jeffersonrocha/Pressao/raw/master/img/2.png)<br/><br/><br/>
> Opção '**procurar**' procure pela data os registro:<br/>
> ![](https://notabug.org/jeffersonrocha/Pressao/raw/master/img/3.png)<br/><br/><br/>
> ![](https://notabug.org/jeffersonrocha/Pressao/raw/master/img/4.png)<br/><br/><br/>
> Opção '**ajuda**' veja à ajuda do pressão:<br/>
> ![](https://notabug.org/jeffersonrocha/Pressao/raw/master/img/5.png)<br/><br/><br/>
> Opção '**versao**' visualize a versão do pressão:<br/>
> ![](https://notabug.org/jeffersonrocha/Pressao/raw/master/img/6.png)<br/><br/><br/>

### Modo de Uso:<br/>
```
-i, inserir
    Questionatário será perguntado 'Data da medição', 'Hora da medição' e 'Pressão Arterial'
    Exemplo de um padrão exato:

    Qual à Data: 18/05/2015
    Qual à Hora: 15:20
    Qual à Pressão: 12x7

    *É importante não deixar nenhum campo nulo, se não o programa fecha.
    No banco de dados será armazenado no formato em linha e caso o usuário peça para 'visualizar'
    será visualizado neste formato:

       DATA              HORA            PRESSÃO
     ========          =========       ===========          
    18/05/2015           15:20             12x7


-v, visualizar
    Visualize todo banco de dados, contendo todas as informações como 'Data' 'Hora' e 'Pressão'.

-p, procurar
    Procure pela 'Data' a informação necessária, exemplo:

    pressao procurar 14/10
    pressao procurar 14
    pressao procurar 14/10/2018

    Será exibido todas a(s) data(s) que coinsidirem.

bloquear
    Bloqueia o banco de dados para não alterações... Arquivo fica somente leitura, nem o root não
    consegue escrever.
    Para está operação é NECESSÁRIO estar logado como root.

desbloquear
    Desbloqueia o banco de dados para alterações.
    Para está operação é NECESSÁRIO estar logado como root.

-a, ajuda
    Mostra à ajuda completa do programa e sai.
```

### Licença:
**MIT** - https://notabug.org/jeffersonrocha/Pressao/raw/master/LICENSE
