**Direção: Conta como núcleo + apostas como operações sobre “estado de jogo”**  
Mobile-first, baseado em **tabs + blocos retangulares → quadrados centrais**, com forte componente gráfico e feedback contínuo.

---

# 1. Estrutura Base (Mobile Tabs)

**Bottom Tabs (fixo):**

- 🏠 **Jogos**
- 🔍 **Buscar**
- 🎯 **Torcida**
- 💼 **Carteira**
- 👤 **Conta**

Cada tab abre uma **stack de cards modulares**, com área central priorizando elementos **quadrados interativos**.

---

# 2. Tela Principal (Jogos) — “Show de Placar”

![https://cdn.dribbble.com/userupload/44689532/file/96a539709dfb2483abdf430213983027.png?resize=400x300](https://cdn.dribbble.com/userupload/44689532/file/96a539709dfb2483abdf430213983027.png?resize=400x300)

![https://cdn.dribbble.com/userupload/20326498/file/still-4318cca74a35af7ea192b5452e3a2823.gif?resize=400x0](https://cdn.dribbble.com/userupload/20326498/file/still-4318cca74a35af7ea192b5452e3a2823.gif?resize=400x0)

![https://cdn.dribbble.com/userupload/43039365/file/original-f7960e22dad57107a73c819b415ce402.png?resize=400x0](https://cdn.dribbble.com/userupload/43039365/file/original-f7960e22dad57107a73c819b415ce402.png?resize=400x0)



### Composição visual

- **Topo:** mini-header com saldo + avatar
- **Centro (hero quadrado):**
    - Placar animado (ex: 1–0)
    - Tempo de jogo (barra circular / radial)
    - Pulsos visuais conforme eventos (gol, perigo)

### Card de Jogo (lista)

Cada jogo = **card retangular → expande para quadrado interativo**

**Estado colapsado:**

- Times + odds rápidas
- Tempo
- Indicador de intensidade (heat)

**Estado expandido (tap):**

- Área quadrada central:
    - Gráfico radial do jogo (posse, pressão)
    - Botões de aposta como “chips” flutuantes
- Swipe horizontal → mercados (gols, escanteios, etc.)

### Mecânica gráfica

- Odds aparecem como **nodos orbitais**
- Tap em nodo = aposta rápida
- Feedback: nodo “entra em órbita” → confirma

---

# 3. Sistema de Conta (Overlay persistente)

### Mini HUD (sempre visível)

- Saldo
- Variação (ganho/perda animado)
- Botão “+” (abrir carteira)

### Interação

- Swipe up → abre **Carteira em modal full-screen**
- Feedback contínuo (pulse, glow) quando há ganhos ativos

---

# 4. Carteira (Wallet Pattern Lúdico)

![https://cdn.dribbble.com/userupload/44181564/file/original-8bdee0491fc44f20ee8b0cad3c7cc213.png?resize=752x&vertical=center](https://cdn.dribbble.com/userupload/44181564/file/original-8bdee0491fc44f20ee8b0cad3c7cc213.png?resize=752x&vertical=center)



![https://cdn.dribbble.com/userupload/45185171/file/9ce348e4c1a04fb6795f37eeb4dac8e7.png?resize=752x&vertical=center](https://cdn.dribbble.com/userupload/45185171/file/9ce348e4c1a04fb6795f37eeb4dac8e7.png?resize=752x&vertical=center)

4

### Estrutura visual

- **Hero central (quadrado):**
    - Núcleo de saldo (círculo energético)
    - Anéis ao redor = apostas ativas

### Componentes

- **Saldo principal (centro pulsante)**
- **Órbitas:**
    - Cada aposta ativa gira ao redor
    - Cor indica risco/estado

### Interações

- Tap em órbita → abre detalhe da aposta
- Drag para fora → cashout
- Long press → editar posição

### Seções abaixo

- Histórico (timeline vertical)
- Créditos promocionais (cards coloridos)

---

# 5. Torcida (Camada Social Semântica)



![https://cdn.dribbble.com/userupload/11175131/file/original-f91901e7173f91879a217f0bf05d8385.png](https://cdn.dribbble.com/userupload/11175131/file/original-f91901e7173f91879a217f0bf05d8385.png)


### Ideia central

Transformar aposta em **energia coletiva**

### UI

- Feed de jogos com:
    - % da torcida em cada lado
    - Emojis reativos (🔥⚡💣)
- “Barra de pressão coletiva”

### Mecânicas

- Entrar em “onda” (seguir multidão)
- Criar “torcida privada”
- Boost coletivo (multiplicador leve)

---