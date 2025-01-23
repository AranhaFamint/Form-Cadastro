Recebi a seguinte missão, realizar cinco testes diferentes em um código de formulário. O primeiro teste foi de verificar o carregamento da página estava correto e com os elementos visuais estáveis, para a realização desse, fiz o seguinte processo:
test('formCadastro', async ({ page }) => {
  await page.goto('file:///C:/Users/Aluno_Noite/Downloads/formCadastro/index.html');
});
 
 O segundo teste era para ver se a mensagem de erro aparecia quando o usuário não preenchia todos os campos, para a realização desse e dos seguintes códigos, comecei a gravar passo a passo do site, fazendo o processo que o teste pedia enquanto o gravava, e depois colocava o que a gravação me retornava e testava para ver se estava certo.

 O terceiro era para ver se o cadastro apareceria na lista dinâmica, usei o recurso de gravação novamente.

 O quarto era para ver se o site evita a duplicação de cadastros, novamente, usei a gravação para isso.

 O quinto era para ver se o botão "limpar" apagaria a lista de cadastros, usei também a gravação para isso.
