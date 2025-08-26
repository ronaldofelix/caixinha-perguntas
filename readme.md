# 📦 Caixinha de Perguntas

Uma aplicação web simples e elegante para criar caixinhas de perguntas personalizadas para redes sociais, especialmente para stories do Instagram.

## ✨ Funcionalidades

- ✏️ **Editor de pergunta**: Campo editável para personalizar sua pergunta
- 📝 **Área de resposta adaptável**: O campo de resposta se ajusta automaticamente ao tamanho do texto
- 🎨 **Design moderno**: Interface minimalista com bordas arredondadas e visual clean
- 📱 **Responsivo**: Funciona perfeitamente em dispositivos móveis e desktop
- 🖼️ **Export PNG**: Baixe sua caixinha como imagem PNG com fundo transparente
- 🚀 **Zero dependências**: Funciona completamente offline após o primeiro carregamento

## 🌐 Demo

Acesse a aplicação em: **[https://seu-usuario.github.io/caixinha-perguntas](https://seu-usuario.github.io/caixinha-perguntas)**

## 🚀 Como usar

1. **Edite a pergunta**: Clique no campo escuro superior e digite sua pergunta
2. **Digite a resposta**: Clique no campo branco e escreva sua resposta
3. **Baixe a imagem**: Clique no botão "📥 Baixar como imagem"
4. **Use nas redes sociais**: Compartilhe a imagem gerada nos seus stories!

## 🛠️ Tecnologias utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com flexbox e bordas arredondadas
- **JavaScript ES6**: Funcionalidades interativas
- **html2canvas**: Biblioteca para captura de screenshot da caixinha

## 📦 Instalação local

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/caixinha-perguntas.git

# Entre no diretório
cd caixinha-perguntas

# Abra o arquivo index.html no navegador
open index.html
```

Ou simplesmente baixe o arquivo `index.html` e abra no seu navegador.

## 🚀 Deploy

### GitHub Pages

1. Faça fork deste repositório
2. Vá em **Settings** > **Pages**
3. Selecione **Deploy from a branch**
4. Escolha **main** como branch e **/ (root)** como pasta
5. Sua aplicação estará disponível em `https://seu-usuario.github.io/caixinha-perguntas`

### Outras plataformas

Esta aplicação pode ser facilmente deployada em:

- **Vercel**: Conecte seu repositório GitHub
- **Netlify**: Faça drag & drop da pasta ou conecte o GitHub
- **GitHub Pages**: Configuração automática
- **Surge.sh**: `surge` no diretório do projeto

## 🎨 Personalização

### Cores

Edite as variáveis CSS no arquivo `index.html`:

```css
/* Cor do cabeçalho */
background: #1c1c1c;

/* Cor do texto do cabeçalho */
color: white;

/* Cor de fundo da resposta */
background: #fff;
```

### Dimensões

```css
/* Largura da caixinha */
.caixinha {
  width: 300px;
}

/* Altura mínima da resposta */
.resposta {
  min-height: 60px;
}
```

## 📱 Casos de uso

- **Stories do Instagram**: Crie perguntas interativas para seus seguidores
- **Posts em redes sociais**: Gere conteúdo visual rapidamente
- **Enquetes e pesquisas**: Formato visual atrativo para perguntas
- **Conteúdo educativo**: Crie cartões de pergunta e resposta
- **Marketing digital**: Templates para campanhas de engajamento

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commitar suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Fazer push para a branch (`git push origin feature/nova-feature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🐛 Reportar bugs

Encontrou um bug? Abra uma [issue](https://github.com/seu-usuario/caixinha-perguntas/issues) descrevendo:

- Navegador e versão
- Sistema operacional
- Passos para reproduzir o problema
- Comportamento esperado vs atual

## ⭐ Suporte

Se este projeto foi útil para você, considere dar uma ⭐ no repositório!

---

Desenvolvido com ❤️ para a comunidade