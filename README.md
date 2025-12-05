# Cartão de TODOS

Página de benefícios e adesão ao Cartão de TODOS com integração World App.

## 🌍 World App Integration

Este projeto está integrado com o ecossistema World App, oferecendo:

### Mini App
A aplicação funciona como um Mini App dentro do World App, proporcionando uma experiência nativa e fluida para os usuários.

- **MiniKit SDK**: Utiliza `@worldcoin/minikit-js` para integração completa
- **Detecção automática**: Identifica quando está rodando dentro do World App
- **Interface adaptativa**: UI otimizada para o ambiente World App

### World ID - Prova de Humanidade
Verificação de identidade segura e privada usando o protocolo World ID:

- **Verificação Orb**: Nível máximo de segurança com escaneamento biométrico
- **Verificação Device**: Opção alternativa mais leve
- **Privacidade preservada**: Zero-knowledge proofs garantem privacidade total
- **Elegibilidade para recompensas**: Usuários verificados têm acesso a benefícios exclusivos

### World Chain
Preparado para integração com a blockchain World Chain:

- Transações rápidas e seguras
- Gas gratuito para usuários verificados
- Compatibilidade EVM (Ethereum Virtual Machine)
- Prioridade de blockspace para humanos verificados

## 🚀 Como Usar

### Dentro do World App
1. Acesse o Mini App através do World App
2. Clique em "Verificar com World ID"
3. Complete a verificação
4. Aproveite os benefícios exclusivos!

### Em Navegadores Externos
1. Baixe o [World App](https://worldcoin.org/download)
2. Crie sua World ID
3. Acesse este site pelo World App para verificação completa

## 🛠️ Desenvolvimento

### Configuração
Para desenvolvedores que desejam modificar a integração:

1. Registre sua aplicação no [World Developer Portal](https://developer.world.org)
2. Obtenha seu `App ID` e `Action ID`
3. Atualize as configurações em `WorldAppConfig` no `index.html`

```javascript
window.WorldAppConfig = {
    appId: 'seu_app_id',
    actionId: 'sua_action_id',
    verificationLevel: 'orb' // ou 'device'
};
```

### Documentação de Referência
- [World Developer Docs](https://docs.world.org/)
- [Mini Apps Quick Start](https://docs.world.org/mini-apps/quick-start/installing)
- [World ID Integration](https://docs.world.org/world-id/id/web-react)
- [World Chain Deployment](https://docs.world.org/world-chain/developers/deploy)
- [MiniKit-JS SDK](https://github.com/worldcoin/minikit-js)

### llms.txt
Para desenvolvedores usando assistentes de IA, consulte:
- [docs.world.org/llms.txt](https://docs.world.org/llms.txt)
- [docs.world.org/llms-full.txt](https://docs.world.org/llms-full.txt)

## ⚠️ Aviso de Deprecação

O "Sign in with World ID v1" está sendo descontinuado. Esta implementação utiliza os caminhos de integração mais recentes conforme a documentação oficial do World Developer.

## 📞 Contato

- **Consultor**: Deivid Curcio
- **WhatsApp**: (22) 99960-4947
- **Formulário**: [Peça seu Cartão](https://form.typeform.com/to/bn74ghpG)

---

© 2025 – Criado por Deivid Curcio | Consultor Cartão de TODOS