
let meta = {
    value: 'ler um livro por mês',
    checked: false,
    //log: (info) => {
    //console.log(info)
    //}
}


//meta.value = "não é mais ler um livro"
//meta.log(meta.value)

// fuction // arrow fuction 
//const criarMeta = () => {}

//function criarMeta () {} 

let metas = [
    meta,
    {
        value: "caminhar 20 minutos por dia",
        checked: false
    }
]

console.log(metas[1].value)


//////////////////////////

## estrutura de repetição

//function start() {
   // console.log("comecou")
//}

//start()

 //segunda opção 

 const start = () => {
    let count = 1
    while(count <= 10){
        console.log(count)
        count = count + 1
        
    }
}
start()

///////////////////////
 
 const start = () => {

    while (true){
        let opcao = "sair"
        switch (opcao) {
            case "cadastrar":
                console.log("vamos cadastrar")
                break
            case "listar":
                console.log("vamos listar")
                break
            case "sair":
                return
        }
    }
}
start()