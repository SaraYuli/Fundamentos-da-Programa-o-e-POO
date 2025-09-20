CLASSE - 
É um modelo que define as características e comportamento de objetos. (um plano, uma receita de bolo). Eu imagino a classe como uma receita de bolo. 
Ela não é o bolo em si, mas sim a ideia de como ele vai ficar.
A receita passa os ingredientes — que seriam os atributos,e o modo de preparo — que seriam os métodos (ou comportamentos).
  

# Atributos (São Características ou propriedades do objeto)

    public String cor;
    public String modelo;
    public int ano;

# Metodos (São as funções ou comportamentos da classe/objeto)

    public void ligar(){
        System.out.println("O carro está ligado");
    }

 # Três perguntas que uma classe teria que responder: 

    1° Coisas que eu tenho?  ---> Atributos 
    2° Coisas que eu faço? -----> Métodos
    3° Como eu estou agora? ----> Estado

Define os atributos e métodos comuns que serão compartilhados por um objeto.



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
OBJETO - 

Uma objeto e uma coisa material ou abstrata que pode ser percebida pelos sentidos e descrita por meio das suas caracterítsticas, comportamentos e estado atual.

Todo objeto tem que vir de uma classe. E quando eu tenho uma classe e quero transformá-la em um objeto, devo instanciar.

# Instanciar

Caneta c1 = new Caneta();


O objeto é a instância de uma classe. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📌 Mini resumo (pra fixar):

Classe → é o molde (ex: a ideia de uma Caneta)

Objeto → é a coisa concreta criada a partir da classe (ex: uma caneta azul na sua mão)

Instanciar → é o ato de criar um objeto a partir da classe

