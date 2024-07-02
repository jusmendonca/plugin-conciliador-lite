# Conciliador Lite 1.0
 
## Versão do plugin Conciliador (beta)

Trata-se de uma extensão para o Google Chrome que auxilia no cálculo de valores de acordos judiciais envolvendo benefícios assistenciais e previdenciários no valor de um salário-mínimo.

O plugin lê planilhas em formato .xlsx e retorna o valor total dos atrasados para a DIB informada, incluindo-o na área de transferência do Windows. Basta, depois, colar o valor no campo próprio da minuta de acordo.

É necessário que a planilha .xslx escolhida corresponda ao benefício, à DIP e ao percentual de desconto do acordo que será proposto.

## Instruções de instalação (Windows)

1. Fazer o download da pasta **plugin-conciliador-lite-main.zip**;

   <img width="318" alt="image" src="https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/264379e4-c7e3-4be5-a3a1-dba3c6d7225b">

2. Descompactar a pasta ("Extrair Tudo");

   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/00b5053c-aecd-4bf4-b1bd-3d6f35dff1dc)
   
3. Escolher o diretório de destino. Recomenda-se descompactar para "C:\Arquivos de Programas". Porém, se você não tiver permissão para alterar esse diretório, salve em "Documentos";

   <img width="440" alt="image" src="https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/c00428d7-ee41-40ca-9516-baf6271d94be">
   
  ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/f3d1ec18-226a-440c-9090-ce49c0bf41e2)

4. Abrir o Google Chrome e digitar chrome://extensions/ na barra de endereços;

   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/2d4d2433-9e81-4324-8641-174159e0f1f8)

5. Ativar o "Modo do desenvolvedor";
   
   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/d050efcd-7c00-49a6-8d14-92fbbc1676f7)

6. Clicar no botão "Carregar sem compactação";

    ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/ec84741c-4298-4216-afb8-a7e0ea5f017f)

7. Selecionar a pasta **plugin-conciliador-lite-main**, onde ela tiver sido salva;

   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/e8e46739-46ee-4e99-9794-49e275b4630f)

8. Aparecerá um ícone (aperto de mãos) ao lado da barra de endereços do navegador, o que significa que a extensão foi instalada corretamente;

    ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/e8f14997-8608-452a-90b7-76378df39114)
    ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/72a56062-8abc-4b25-bf94-9376ca386889)

9. Fixe o Conciliador Lite na barra de extensões do seu navegador, para facilitar o acesso.

    <img width="224" alt="image" src="https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/c18092c3-bdb8-4f32-b9ca-2f19104576a1">

## Instruções de uso

1. As planilhas a serem usadas estarão na pasta "Planilhas", dentro da pasta **plugin-conciliador-lite-main**. Antes do uso, verifique se você dispõe das planilhas de que precisa. Cada planilha corresponde a uma classe de benefícios (BPC-LOAS ou RURAL), um percentual de acordo (90, 95, 100) e uma DIP (Data de Inicío do Pagamento). Desse modo, no início de cada mês, você deverá fazer o download das planilhas atualizadas que for usar. Caso contrário, terá que ajustar a minuta conforme a DIP da planilha da qual você dispõe;
2. Se você já tiver a planilha correta, clique no ícone da extensão no Google Chrome (aperto de mãos);
3. A extensão abrirá a seguinte janela:

![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/142ab693-93a0-4057-b804-306e3b8d8226)

4. Nessa janela, você deverá escolher a planilha adequada, clicando em "Escolher arquivo";
5. Digite a DIB do acordo, no formato DD/MM/AAAA;
6. Clique no botão "CALCULAR E COPIAR" ou tecle ENTER. O resultado será semelhante a este:

![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/90155799-6548-41b4-b306-932954ce3c74)

7. Agora, basta colar (com Ctrl+V ou botão direito do mouse) o valor do acordo no campo próprio da minuta e salvá-la.

## Atualização das planilhas

Mensalmente, será gerada uma nova planilha para a DIP no primeiro dia do mês corrente. Para fazer o download da nova planilha, navegue até a pasta desejada e faça o download da planilha:

<img width="342" alt="image" src="https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/92146698-094d-413c-96cf-488c4358e93e">


<img width="521" alt="image" src="https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/722cd0b9-1b94-4a43-99e5-2a7686db7c20">


<img width="367" alt="image" src="https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/e85e3c99-769e-4aa9-956e-930011731734">


<img width="368" alt="image" src="https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/c916dd43-e62c-498f-a905-4c9a3f4e64cc">

Depois, salve na pasta "planilhas", que está dentro da pasta **plugin-conciliador-lite-main**. Quando for usar a planilha com a nova DIP pela primeira vez, selecione-a.

## Observações

1. A extensão guarda na memória os dados do último arquivo selecionado e da última DIB. Para trabalhar sequencialmente em várias propostas de acordo, basta alterar a DIB.
2. O plugin lê apenas arquivos xlsx pré-formatados.
3. Esta é uma versão de testes. É responsabilidade do proponente conferir os valores da proposta, bem como seus parâmetros.
