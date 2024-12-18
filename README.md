# Nivel-Saldo-do-Her-i
let numeroVitorias = 9
let numeroDeDerrotas = 4
let saldoVitorias = saldoRakeado(numeroVitorias,numeroDeDerrotas)

function saldoRakeado(num1,num2) {
    let subtracao = num1 - num2
    return subtracao
}

  if (numeroVitorias < 10) {
        nivel= "Ferro"
      
  }else if ((numeroVitorias >= 11)&(numeroVitorias <= 20)){
        nivel = "Bronze"
        
  }else if ((numeroVitorias >= 21)&(numeroVitorias <= 50)){
        nivel = "Prata"
        
        
  }else if ((numeroVitorias >= 51)&(numeroVitorias <= 80)){
        nivel = "Ouro"
      
  }else if ((numeroVitorias >= 81)&(numeroVitorias <= 90)){
        nivel = "Dimante"
      
  }else if ((numeroVitorias >= 91)&(numeroVitorias <= 100)){
      nivel = "Lendario"
      
      
      
  }else{
      nivel = "Imortal" 
      
  }
  

console.log(`O Heroí tem o saldo de ${saldoVitorias} e está no nivel de ${nivel}`);



