function recomendarFilme(idade) {
    if (idade < 10) {
        return "Recomendação: A Pequena Sereia";
    } else if (idade >= 10 && idade < 15) {
        return "Recomendação: O Homem-Aranha";
    } else if (idade >= 15 && idade < 18) {
        return "Recomendação: Barbie";
    } else if (idade >= 18) {
        return "Recomendação: Invocação do Mal";
    } else {
        return "Idade inválida.";
    }
}

// Exemplo de uso:
const idadeUsuario = 16; // Insira a idade do usuário aqui
console.log(recomendarFilme(idadeUsuario));
