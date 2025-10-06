# 🙏 Paróquia São Roque - Cruzeiro

Site institucional da Paróquia São Roque, localizada em Jundiaí - SP. Desenvolvido com HTML, CSS e JavaScript puro, focado em responsividade e experiência do usuário.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Sobre o Projeto

Este site foi desenvolvido para fornecer informações essenciais sobre a Paróquia São Roque (Matriz) e suas duas comunidades: São Sebastião e Nossa Senhora Aparecida, todas localizadas em Jundiaí - SP.

### Informações Disponíveis:

- ⛪ Horários de missas (Matriz e Comunidades)
- 👥 Informações da equipe pastoral completa
- 📍 Dados de contato e localização das 3 igrejas
- 🕐 Horários de atendimento da secretaria paroquial
- 📱 Links diretos para redes sociais, telefone e WhatsApp
- 🗺️ Integração com Google Maps para localização

## ✨ Funcionalidades

- 🎨 **Design Responsivo**: Adaptável para desktop, tablet e mobile
- 🍔 **Menu Hambúrguer**: Navegação intuitiva em dispositivos móveis
- 🎭 **Animações Suaves**: Elementos aparecem gradualmente ao rolar a página
- 📱 **Ícones Intuitivos**: Font Awesome para melhor experiência visual
- 🔗 **Navegação Suave**: Scroll suave entre seções do site
- 📞 **Links Diretos**: Click-to-call para telefone e WhatsApp (funciona em mobile)
- 📧 **Email Clicável**: Abre automaticamente o cliente de email
- 🗺️ **Integração Google Maps**: Link direto para localização da paróquia
- 🎨 **Efeito Parallax**: Imagem de fundo com efeito de profundidade
- 🌈 **Navbar Dinâmica**: Muda de cor ao rolar a página
- 👆 **Fechar Menu Automático**: Menu mobile fecha ao clicar em link ou fora dele
- ⛪ **3 Locais de Missa**: Informações da matriz e duas comunidades

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização e animações
- **JavaScript**: Interatividade e funcionalidades
- **Font Awesome 6.4.0**: Biblioteca de ícones

## 📁 Estrutura do Projeto

```
paroquia-sao-roque/
│
├── index.html              # Estrutura principal do site
├── styles.css              # Estilos e design
├── script.js               # Funcionalidades JavaScript
└── README.md               # Documentação do projeto
```

## 🔧 Como Usar

### Pré-requisitos

Nenhum! Apenas um navegador web moderno.

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/paroquia-sao-roque.git
```

2. Navegue até a pasta do projeto:
```bash
cd paroquia-sao-roque
```

3. Abra o arquivo `index.html` no navegador:
```bash
# No Windows
start index.html

# No Mac
open index.html

# No Linux
xdg-open index.html
```

4. **Configure os links das redes sociais**:
   - Abra o arquivo `index.html`
   - Localize a seção `<footer>` (próximo ao final)
   - Substitua os `#` pelos links reais do Facebook e Instagram da paróquia

## 🎨 Personalização

### Alterando as Cores

Edite as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary-color: #8B4513;      /* Cor principal */
    --secondary-color: #D4AF37;    /* Cor secundária */
    --dark-color: #2c1810;         /* Cor escura */
    --light-color: #f5f5f5;        /* Cor clara */
    --white: #ffffff;              /* Branco */
}
```

### Alterando as Redes Sociais

No arquivo `index.html`, localize a seção de redes sociais no footer (final do arquivo) e **substitua os `#` pelos links reais**:

```html
<div class="social-links">
    <a href="URL_COMPLETA_DO_FACEBOOK" target="_blank" title="Facebook">
        <i class="fab fa-facebook"></i>
    </a>
    <a href="URL_COMPLETA_DO_INSTAGRAM" target="_blank" title="Instagram">
        <i class="fab fa-instagram"></i>
    </a>
</div>
```

**Exemplo:**
```html
<a href="https://www.facebook.com/paroquiasaoroque" target="_blank" title="Facebook">
```

### Alterando a Imagem de Fundo

1. **Opção 1**: Substitua o arquivo `igreja-paroquia.jpg` pela sua imagem (mantenha o mesmo nome)

2. **Opção 2**: Use outro nome de arquivo alterando no `styles.css` (linha 56):

```css
.hero {
    background: linear-gradient(rgba(44, 24, 16, 0.5), rgba(44, 24, 16, 0.6)), 
                url('NOME-DA-SUA-IMAGEM.jpg');
}
```

**Dica**: Para melhor qualidade visual, use imagens com resolução mínima de 1920x1080px.

## 📱 Responsividade

O site é totalmente responsivo e otimizado para:

- 📱 Smartphones (320px+)
- 📱 Tablets (768px+)
- 💻 Laptops (1024px+)
- 🖥️ Desktops (1200px+)

## 🌐 Navegadores Suportados

- ✅ Google Chrome (recomendado)
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari
- ✅ Opera

## 📞 Informações de Contato

### 🏛️ Paróquia São Roque - Cruzeiro (Matriz)

- 📍 Rua Victório Gropello 110 – Vila Progresso – Jundiaí – SP
- 📮 CEP: 13202-180
- ☎️ Telefone: (11) 4587-5224
- 📱 WhatsApp: (11) 4587-5224
- ✉️ Email: secretaria.paroquiasaoroque@gmail.com

**Horários de Missas:**
- Terça-feira: 19h
- Quinta-feira: 19h
- Sexta-feira: 19h (somente na 1ª sexta-feira do mês)
- Sábado: 18h30
- Domingo: 9h30 e 18h

**Atendimento da Secretaria:**
- Segunda-feira: 13h às 17h
- Terça a Sexta: 8h às 12h e 13h às 17h
- Sábado: 8h às 11h30

---

### ⛪ Comunidade São Sebastião

- 📍 Rua Zurich 30 – Vila São Sebastião – Jundiaí – SP
- ☎️ Telefone: (11) 4587-5224

**Horários de Missas:**
- Sábado: 17h

---

### ⛪ Comunidade Nossa Senhora Aparecida

- 📍 Rua José Maria Marinho 160 – Vila Agrícola – Jundiaí – SP
- ☎️ Telefone: (11) 4587-5224

**Horários de Missas:**
- Domingo: 8h

## 👥 Equipe Pastoral

- **Pároco**: Padre Venilton Calheiros
- **Diácono Permanente**: Diácono Pedro Alves Moreira
- **Diácono Emérito**: Diácono Antonio Jesualdo Begiato
- **Auxiliares Administrativas**: 
  - Lidia Paiva Scarabello
  - Elaine Cristina Mendes

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma Branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Desenvolvido com ❤️ e ☕ para a Paróquia São Roque

---

## 🙏 Agradecimentos

- Paróquia São Roque e toda a comunidade
- Font Awesome pela biblioteca de ícones
- Todos que contribuíram com sugestões e melhorias

---

**⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!**

**🔔 Fique por dentro das atualizações seguindo o repositório!**
