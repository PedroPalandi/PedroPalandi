<!--## Olá, me chamo Pedro. 😉 ## 
Sou aluno do Senai e estou aprendendo a programar e desenvolver sistemas.
Como comecei este ano -->
// ⚠️ Atenção: código altamente motivado por café ☕️

const dev = {
  nome: "Seu Nome",
  bugsCriados: Infinity,
  bugsResolvidos: Math.random() > 0.5 ? "Sim" : "Talvez",
  cafeConsumido: "Sempre insuficiente",
  status: "Compilando…",
};

function programar() {
  while (dev.cafeConsumido !== "suficiente") {
    console.log("☕ Bebendo café...");
    dev.cafeConsumido = "Ainda não";
  }
}

function deploy() {
  try {
    console.log("🚀 Fazendo deploy...");
    throw "Erro misterioso que some amanhã";
  } catch (erro) {
    console.log("🐛 Bug encontrado:", erro);
  } finally {
    console.log("😎 Funcionou na minha máquina");
  }
}

programar();
deploy();

