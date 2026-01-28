## Tradução PT-BR para Magento 1.9.x 🇧🇷

Esta é a tradução base mais completa e atualizada para o ecossistema Magento 1.9.x. O objetivo deste projeto é fornecer uma localização impecável, corrigindo termos genéricos e padronizando a experiência de compra para o mercado brasileiro.

## 🚀 Destaques desta tradução

    - Tradução Completa: Abrange Frontend e Backend (Admin).
    - Padronização: Termos fiscais e de checkout ajustados para o Brasil.
    - Compatibilidade: Testado em todas as subversões da linha 1.9.x.

## 🛠️ Como Instalar

### Método 1: Via Git (Recomendado)

Se você tem acesso ao terminal do seu servidor, execute:
```bash
cd /caminho/da/sua/loja
git clone https://github.com/mariosam/Traducao-PT-BR-Magento-1.9.x.git temp_trans
cp -r temp_trans/* .
rm -rf temp_trans
```

### Método 2: Manual (Mais Simples)

- Baixe o arquivo .zip.
- Extraia o conteúdo.
- Envie as pastas app e lib para a raiz da sua instalação Magento via FTP/SFTP.

## ⚙️ Configuração Pós-Instalação

Após enviar os arquivos, ative a tradução no painel administrativo:

- Vá em System > Configuration.
- No menu lateral esquerdo, em General, clique em General.
- Na aba Locale Options, altere o Locale para Portuguese (Brazil).
- Limpe o cache em System > Cache Management.

## Mais Detalhes no Blog do Mario SAM

https://mage.mariosam.com.br/traducao-magento/

## 🤝 Como Contribuir

Encontrou um erro de digitação ou um termo que pode ser melhorado?

- Faça um Fork do projeto.
- Crie uma Branch para sua modificação (git checkout -b feature/melhoria-termo).
- Faça o Commit (git commit -m 'Correção do termo X no checkout').
- Envie um Push (git push origin feature/melhoria-termo).
- Abra um Pull Request.

## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo LICENSE para detalhes.

### ⭐ Gostou do projeto? Considere dar uma estrela no repositório para ajudar na visibilidade!