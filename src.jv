// Função para classificar o nível do herói
function classificarHeroi(nome, xp) {
  let nivel;

  if (xp < 1000) {
    nivel = "Ferro";
  } else if (xp <= 2000) {
    nivel = "Bronze";
  } else if (xp <= 5000) {
    nivel = "Prata";
  } else if (xp <= 7000) {
    nivel = "Ouro";
  } else if (xp <= 8000) {
    nivel = "Platina";
  } else if (xp <= 9000) {
    nivel = "Ascendente";
  } else if (xp <= 10000) {
    nivel = "Imortal";
  } else {
    nivel = "Radiante";
  }

  console.log(`O Herói de nome ${nome} está no nível de ${nivel}`);
}

// Obtendo entradas do usuário
let nomeHeroi = prompt("Digite o nome do herói:");
let xpHeroi = parseInt(prompt("Digite a quantidade de experiência (XP) do herói:"));

// Classificando e exibindo o nível do herói
classificarHeroi(nomeHeroi, xpHeroi);
