# SheGlow — Briefing Tecnico para Designer de Embalagens

> Entregar este arquivo ao designer junto com o mockup HTML (embalagens.html)

---

## 1. Visao Geral

**Marca:** SheGlow
**Tagline:** Cada fase, um brilho
**Categoria:** Nutraceuticos premium femininos 30+
**Posicionamento visual:** Luxo acessivel. Clean, minimalista, sofisticado. Referencia visual: Aesop, Ritual, The Nue Co.

---

## 2. Arquivos Necessarios

Para CADA produto, o designer deve entregar:

- [ ] Rotulo frontal (arquivo AI/PDF vetorial, CMYK, com sangria 3mm)
- [ ] Rotulo traseiro (tabela nutricional, informacoes legais, codigo de barras)
- [ ] Mockup 3D fotorrealista do frasco (PNG transparente, 3000x3000px)
- [ ] Arte da caixa externa (planificada, com dieline)
- [ ] Arquivo aberto editavel (para futuros ajustes)

---

## 3. Especificacoes do Frasco

### Glow Essentials (GlowHair, GlowFocus, GlowShield, GlowEnergy)
- **Tipo:** Frasco cilindrico com tampa rosca
- **Material:** PEAD (plastico opaco) ou vidro ambar fosco (preferencial)
- **Capacidade:** 60 capsulas / 60 comprimidos
- **Altura estimada:** 10-12cm
- **Diametro estimado:** 5-6cm
- **Tampa:** Dourada (metalizada ou fosca)

### GlowSkin (Colageno em po)
- **Tipo:** Pote cilindrico largo
- **Material:** PEAD ou vidro
- **Capacidade:** 567g
- **Altura estimada:** 12-14cm
- **Diametro estimado:** 10cm
- **Tampa:** Dourada

---

## 4. Design do Rotulo Frontal

### Hierarquia visual (de cima para baixo):

```
1. Logo "SheGlow" (Playfair Display, 600 weight)
   - "She" em preto (#1C1C1C)
   - "Glow" em italico, na cor do produto

2. Linha decorativa fina (cor do produto, 30px largura)

3. Nome do produto (Playfair Display, 700 weight)
   - Ex: "GlowHair" — "Glow" em preto, "Hair" em italico cor do produto
   - Tamanho: destaque principal do rotulo

4. Promessa (Inter, 500 weight, uppercase, tracking 0.08em)
   - Ex: "Cabelo forte · Pele luminosa · Unhas resistentes"
   - Cor: #555 (cinza medio)
   - Tamanho: pequeno, discreto

5. Linha divisoria fina (rgba 0,0,0, 0.06)

6. Informacoes de formato (DM Mono ou Inter Mono)
   - Ex: "60 capsulas vegetais · 30 dias"
   - Cor: #999 (cinza claro)

7. Badges (pills com borda fina)
   - Ex: "Sem gluten" "Sem lactose"
   - Borda: rgba(0,0,0,0.08), border-radius 100px
```

### Estilo geral:
- Fundo do rotulo: branco com leve transparencia (se frasco for colorido)
- Bordas do rotulo: arredondadas suaves (6px radius)
- Espacamento generoso entre elementos
- NENHUMA imagem, foto ou ilustracao no rotulo — puramente tipografico
- Acabamento: laminacao fosca + hot stamping dourado no logo (se orcamento permitir)

---

## 5. Cores por Produto

| Produto | Cor principal | Hex | Uso |
|---|---|---|---|
| **GlowHair** | Rose | `#C4929A` | Frasco, "Hair" no rotulo, tampa |
| **GlowSkin** | Azul oceano | `#6BA8B8` | Frasco, "Skin" no rotulo |
| **GlowFocus** | Dourado | `#BFA15E` | Frasco, "Focus" no rotulo |
| **GlowShield** | Ambar | `#D4A040` | Frasco, "Shield" no rotulo |
| **GlowEnergy** | Sage/verde | `#8FA888` | Frasco, "Energy" no rotulo |

**Tampa de todos:** Dourado metalizado `#D4B85A` → `#B89830` (gradiente)

**Texto preto:** `#1C1C1C`
**Texto cinza medio:** `#555555`
**Texto cinza claro:** `#999999`

---

## 6. Tipografia

| Uso | Fonte | Peso | Observacao |
|---|---|---|---|
| Logo "SheGlow" | Playfair Display | 600 | "Glow" sempre em italico |
| Nome do produto | Playfair Display | 700 | Segunda palavra em italico |
| Promessa / subtitulo | Inter | 500 | Uppercase, letter-spacing 0.08em |
| Formato / caps | DM Mono ou Inter | 400 | Monospacado, uppercase |
| Badges | Inter | 600 | 6-7pt, uppercase |
| Tabela nutricional (verso) | Inter | 400/600 | Conforme RDC ANVISA |

**Google Fonts (gratuitas):**
- Playfair Display: https://fonts.google.com/specimen/Playfair+Display
- Inter: https://fonts.google.com/specimen/Inter
- DM Mono: https://fonts.google.com/specimen/DM+Mono

---

## 7. Rotulo Traseiro (Verso)

### Elementos obrigatorios:

1. **Tabela nutricional** (conforme IN 28/2018 da ANVISA)
   - Porcao, %VD, lista de nutrientes
   - A preencher pelo fabricante

2. **Ingredientes** (ordem decrescente de quantidade)
   - A preencher pelo fabricante

3. **Modo de uso** (ver mockup HTML para texto de cada produto)

4. **Advertencias obrigatorias:**
   - "Este produto nao e um medicamento"
   - "Nao exceder a recomendacao diaria"
   - "Gestantes, nutrizes e criancas ate 3 anos..."
   - "Mantenha fora do alcance de criancas"

5. **Dados do fabricante:**
   - Razao social, CNPJ, endereco, telefone SAC

6. **Codigo de barras** (EAN-13)

7. **Numero de notificacao ANVISA**

8. **QR code** (link para certificado de analise do lote)

9. **Selo "SheGlow"** discreto

---

## 8. Caixa Externa

### Estilo:
- **Papel:** Triplex 300g com laminacao fosca
- **Cor base:** Off-white / creme `#FDFBF8`
- **Impressao:** 1 cor (preto) + hot stamping dourado (logo e detalhes)
- **Formato:** Caixa tipo luva ou tuck-end

### Layout da caixa:
- **Frente:** Logo SheGlow + nome do produto + promessa
- **Verso:** Modo de uso + informacoes legais
- **Lateral:** Logo SheGlow + cor do produto
- **Topo:** Selo de lacre

### Acabamento premium:
- Hot stamping dourado no logo (frente)
- Relevo seco no nome do produto (se orcamento permitir)
- QR code no verso

---

## 9. Entregas e Prazos Sugeridos

| Fase | Entrega | Prazo sugerido |
|---|---|---|
| 1 | Conceitos iniciais (2-3 opcoes de rotulo GlowHair) | 5 dias uteis |
| 2 | Aprovacao + ajustes | 3 dias uteis |
| 3 | Finalizacao dos 5 rotulos (frente + verso) | 7 dias uteis |
| 4 | Mockups 3D fotorrealistas | 3 dias uteis |
| 5 | Arte da caixa externa | 5 dias uteis |
| **Total** | | **~23 dias uteis** |

---

## 10. Referencias Visuais

Marcas para o designer estudar:
- **Aesop** — minimalismo tipografico farmaceutico
- **Ritual** — frasco transparente amarelo, rotulo clean
- **The Nue Co** — farmaceutico de luxo
- **Seed** — caixa premium com refil system
- **Byredo** — perfumaria minimalista (referencia de acabamento)

**O que NAO queremos:**
- Fotos de ingredientes no rotulo (nada de folhas, frutas, moleculas)
- Cores neon ou vibrantes demais
- Fontes sans-serif genericas (Helvetica, Arial)
- Layout lotado de informacao na frente
- Estilo "farmacia" ou "GNC"
