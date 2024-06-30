# Conciliador Lite 1.0
 
## Versão do plugin Conciliador BETA

Trata-se de uma extensão para o Google Chrome que auxilia no cálculo de valores de acordos judiciais envolvendo benefícios assistenciais e previdenciários no valor de um salário-mínimo.
O plugin lê planilhas em formato .xlsx e retorna o valor total dos atrasados para a DIB informada, incluindo-o na área de tranferência do Windowns. Basta, portanto, colar o valor para o campo próprio da minuta de acordo.
É necessário que a planilha .xslx escolhida corresponda ao benefício, à DIP e ao percentual de desconto do acordo que será proposto.

## Intruções de instalação

1. Fazer o download da pasta **plugin-conciliador-lite**, salvando-a no disco rígido (sugere-se a pasta "Arquivos de Programas");
2. Abrir o Google Crhome e digitar chrome://extensions/ na barra de endereços;

   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/2d4d2433-9e81-4324-8641-174159e0f1f8)

3. Ativar o "Modo do desenvolvedor";
   
   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/d050efcd-7c00-49a6-8d14-92fbbc1676f7)

4. Clicar no botão "Carregar sem compactação";

    ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/ec84741c-4298-4216-afb8-a7e0ea5f017f)

5. Selecionar a pasta **plugin-conciliador-lite**, onde ela tiver sido salva;

   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/39b1b21e-29eb-4ee4-874b-d7936eaca9d5)

6. Aparecerá um ícone (aperto de mãos) ao lado da barra de endereços do navegador, o que significa que a extensão foi instalada corretamente;

    ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/e8f14997-8608-452a-90b7-76378df39114)
   ![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/72a56062-8abc-4b25-bf94-9376ca386889)

## Instruções de uso

1. As planilhas a serem usadas estarão na pasta "Planilhas", dentro da pasta **plugin-conciliador-lite**. Antes do uso, verifique se você dispõe das planilhas de que precisa. Cada planilha corresponde a uma classe de benefícios (BPC-LOAS ou RURAL), um percentual de acordo (90, 95, 100) e uma DIP (Data de Inicío do Pagamento). Desse modo, no início de cada mês, você deverá fazer o download das planilhas atualizadas que for usar. Caso contrário, terá que ajustar a minuta conforme a DIP da planilha da qual você dispõe;
2. Se você já tiver a planilha correta, clique no ícone da extensão no Google Chrome (aperto de mãos);
3. A extensão abrirá a seguinte janela:

![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/142ab693-93a0-4057-b804-306e3b8d8226)

4. Nessa janela, você deverá escolher a planilha adequada, clicando em "Escolher arquivo";
5. Digite a DIB do acordo, no formato DD/MM/AAAA;
6. Clique no botão "CALCULAR E COPIAR" ou tecle ENTER. O resultado será semelhante a este:

![image](https://github.com/jusmendonca/plugin-conciliador-lite/assets/132851772/90155799-6548-41b4-b306-932954ce3c74)

7. Agora, basta colar (com Ctrl+V ou botão direito do mouse) o valor do acordo no campo próprio da minuta e salvá-la.

## Observações

1. A extensão guarda na memória os dados do último arquivo selecionado e da última DIB. Para trabalhar sequencialmente com várias propostas de acordo, basta alterar a DIB.
2. O plugin lê apenas arquivos xlsx pré-formatados.
3. Esta é uma versão de testes. É responsabilidade do proponente conferir os valores da proposta, bem como seus parâmetros.
