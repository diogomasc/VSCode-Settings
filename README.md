# Editando `settings.json` no Visual Studio Code

Para personalizar as configurações do Visual Studio Code, você pode editar diretamente o arquivo `settings.json`.

## Abrir `settings.json` (Windows)

No Visual Studio Code:

- Pressione `Ctrl + Shift + P` para abrir o menu de comandos.
- Digite "Preferences: Open User Settings (JSON)" e pressione Enter.

ou

- No menu superior, clique em **Code** e selecione **Preferences** > **Settings**.
- Na barra de pesquisa de configurações, digite "json" e selecione **Edit in settings.json** na lista de resultados.

O arquivo `settings.json` será aberto para edição.

## Exemplo de Formato

```json
{
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "workbench.colorTheme": "Min Dark",
  // Adicione ou modifique suas configurações aqui
}
```

## Salvar Alterações

- Após fazer as alterações desejadas, salve o arquivo `settings.json` (Ctrl + S no Windows, Cmd + S no macOS).

## Configurações Pré-definidas

Você pode copiar e colar as configurações fornecidas acima diretamente no seu `settings.json`. Certifique-se de instalar as seguintes fontes para obter a melhor experiência visual:

- **JetBrains Mono**: Fonte usada no editor e terminal.
  - Download direto: [JetBrainsMono.zip](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/JetBrainsMono.zip)
- **Inter**: Fonte usada para o tema APC.
  - Download direto: [Inter.zip](https://rsms.me/inter/download/)

## Extensões usadas

- **APC Customize UI++**: Para personalizar ainda mais a interface do Visual Studio Code.
  - Baixe a extensão em [APC Customize UI++](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.apccustomizeui).
  
- **Min Theme**: Um tema elegante para o Visual Studio Code.
  - Baixe a extensão em [Min Theme](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.min-theme).

- **Symbols**: Adiciona ícones elegantes para melhorar a experiência visual no VS Code.
  - Baixe a extensão em [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols).
