# Mapa de Conexão - ASUS TUF GAMING B850M-PLUS

## Especificações do Sistema

### Componentes do Build
- **Processador**: AMD Ryzen 7 7800X3D (8-Core, 16-Threads, AM5)
- **Placa de Vídeo**: XFX RX 9060 XT 16GB
- **SSD**: Kingston NV3 1TB M.2 NVMe (PCIe 4.0)
- **Memória RAM**: Kingston Fury Beast 16GB DDR5 6000MHz CL36
- **Placa-Mãe**: ASUS TUF GAMING B850M-PLUS (AMD AM5, mATX, DDR5)
- **Water Cooler**: Corsair Nautilus 240 RS (240mm)
- **Fonte**: Pichau Cluster 850W PCIe 5.0 Full Modular 80 Plus Gold
- **Gabinete**: LIAN LI Vector V100
- **Ventiladores**: 1 exaustor traseiro + 3 ventiladores laterais (ARGB)

---

## 1. INSTALAÇÃO DO PROCESSADOR (CPU)

### Socket AM5
1. Levante a alavanca do socket AM5
2. Alinhe o triângulo dourado do AMD Ryzen 7 7800X3D com o triângulo do socket
3. Coloque o processador cuidadosamente no socket (sem pressão)
4. Abaixe a alavanca para travar o processador

⚠️ **ATENÇÃO**: Não force o processador. Ele deve encaixar naturalmente.

---

## 2. INSTALAÇÃO DA MEMÓRIA RAM

### Slots DDR5 (DIMM_A1, DIMM_A2, DIMM_B1, DIMM_B2)

**Configuração Recomendada para 1x 16GB:**
- Instale no slot **DIMM_A2** (segundo slot a partir da CPU)
- Para melhor desempenho em single-channel

**Se adicionar um segundo módulo no futuro:**
- Use os slots **DIMM_A2** e **DIMM_B2** (2º e 4º slots) para dual-channel

**Instalação:**
1. Abra as travas laterais do slot
2. Alinhe o entalhe da memória com o slot
3. Pressione firmemente até ouvir um clique
4. As travas laterais devem fechar automaticamente

---

## 3. INSTALAÇÃO DO SSD M.2 NVMe

### Slot M.2_1 (PCIe 5.0 x4)
- **Localização**: Entre o socket da CPU e o primeiro slot PCIe
- **Suporte**: PCIe 5.0 x4 (compatível com o Kingston NV3 PCIe 4.0)

**Instalação:**
1. Remova o dissipador térmico M.2 pré-instalado (se houver)
2. Remova o parafuso de montagem do slot M.2_1
3. Insira o SSD Kingston NV3 no slot em ângulo de 30°
4. Pressione o SSD para baixo
5. Fixe com o parafuso de montagem
6. Recoloque o dissipador térmico M.2

⚠️ **NOTA**: O slot M.2_1 é o principal e oferece a melhor performance

---

## 4. INSTALAÇÃO DO WATER COOLER (Corsair Nautilus 240 RS)

### A. Preparação do Suporte (Backplate)
1. Remova o suporte AM4/AM5 padrão da placa-mãe (se necessário)
2. Instale o backplate AM5 do Corsair na parte traseira da placa
3. Fixe os espaçadores através dos orifícios da placa-mãe

### B. Instalação da Unidade da Bomba
1. Aplique pasta térmica no processador (se não vier pré-aplicada no cooler)
2. Alinhe o suporte e a bomba sobre os parafusos dos espaçadores
3. Aperte as porcas de aperto manual (F) em padrão cruzado (diagonal)
4. Comece apertando levemente todos os cantos
5. Depois aperte firmemente em padrão cruzado até que os quatro cantos estejam uniformemente apertados

### C. Instalação do Radiador 240mm
**Localização no Gabinete LIAN LI Vector V100:**
- **Posição Recomendada**: Parte superior ou frontal do gabinete
- **Orientação**: Tubos para baixo (para evitar ruído de bolhas de ar)

**Fixação:**
1. Posicione o radiador na parte interna do gabinete
2. Alinhe com os orifícios de montagem
3. Fixe com os parafusos incluídos

---

## 5. CONEXÕES DA PLACA-MÃE - MAPA DETALHADO

### 5.1 CONEXÕES DA CPU E COOLER

#### CPU_FAN (Conector PWM 4 pinos próximo ao socket da CPU)
**Conectar**: Cabo PWM de 4 pinos da bomba do Water Cooler Corsair Nautilus 240 RS
- **Localização**: Parte superior esquerda da placa, próximo ao socket AM5
- **Função**: Alimentação e controle da bomba do water cooler
- ⚠️ **IMPORTANTE**: A bomba DEVE ser conectada aqui para funcionamento adequado

#### CPU_OPT (Conector PWM 4 pinos adicional)
**Opcional**: Pode ser usado para um ventilador adicional de CPU
- **Localização**: Próximo ao conector CPU_FAN
- **Função**: Ventilador auxiliar de CPU (não usado neste build)

---

### 5.2 CONEXÕES DOS VENTILADORES (FANS)

A placa ASUS TUF GAMING B850M-PLUS possui vários conectores para ventiladores:

#### CHA_FAN1 (Chassis Fan 1 - PWM 4 pinos)
**Conectar**: Cabo de extensão PWM (K) das ventoinhas do radiador do water cooler (2x ventiladores de 120mm)
- **Localização**: Parte inferior direita da placa
- **Função**: Controle dos ventiladores do radiador (conectados em série)
- **Configuração**: As duas ventoinhas do radiador são conectadas em série (daisy-chain) e depois ao cabo de extensão PWM

#### CHA_FAN2 (Chassis Fan 2 - PWM 4 pinos)
**Conectar**: Ventilador exaustor traseiro
- **Localização**: Parte inferior da placa, próximo ao CHA_FAN1
- **Função**: Ventilador de exaustão traseiro (120mm ou 140mm)
- **Orientação**: Ar saindo do gabinete

#### CHA_FAN3 (Chassis Fan 3 - PWM 4 pinos)
**Conectar**: Hub/Splitter para os 3 ventiladores laterais
- **Localização**: Parte média direita da placa
- **Função**: Controle dos 3 ventiladores laterais
- **Orientação**: Modo reverse (ar entrando no gabinete)
- ⚠️ **NOTA**: Use um hub PWM ou splitter Y para conectar os 3 ventiladores

---

### 5.3 CONEXÕES ARGB (Iluminação RGB Endereçável)

#### ADD_GEN2_1 e ADD_GEN2_2 (Conectores ARGB 3 pinos)
**Conectar**: Cabos ARGB dos ventiladores
- **Localização**: Parte inferior da placa-mãe
- **Pinagem**: +5V, Data, Ground (3 pinos)
- **Função**: Controle de iluminação RGB endereçável via ASUS Aura Sync

**Configuração Recomendada:**
- **ADD_GEN2_1**: Ventilador exaustor traseiro (se tiver ARGB)
- **ADD_GEN2_2**: Hub ARGB para os 3 ventiladores laterais + ventiladores do radiador (se tiverem ARGB)

⚠️ **IMPORTANTE**: 
- Conectores ARGB são de 3 pinos (5V)
- NÃO confunda com conectores RGB tradicionais de 4 pinos (12V)
- Use um hub/controller ARGB se precisar conectar mais de 2 dispositivos

---

### 5.4 SLOT PCIe PARA PLACA DE VÍDEO

#### PCIE_1 (PCIe 5.0 x16)
**Conectar**: XFX RX 9060 XT 16GB
- **Localização**: Primeiro slot PCIe x16 (mais próximo da CPU)
- **Suporte**: PCIe 5.0 x16 (velocidade máxima)
- **Fixação**: 
  1. Remova as coberturas de slot do gabinete
  2. Alinhe a placa de vídeo com o slot
  3. Pressione firmemente até ouvir um clique
  4. Fixe com parafusos no gabinete

⚠️ **ATENÇÃO**: Use SEMPRE o primeiro slot PCIe x16 para melhor desempenho

---

### 5.5 CONEXÕES DE ALIMENTAÇÃO (PSU)

#### Conexões da Fonte Pichau Cluster 850W

**1. ATX_24PIN (Conector Principal 24 pinos)**
- **Localização**: Lado direito da placa-mãe
- **Cabo**: Cabo principal ATX 24 pinos (20+4)
- **Função**: Alimentação principal da placa-mãe

**2. ATX_12V_2x4 (Conector CPU 8 pinos)**
- **Localização**: Parte superior esquerda, próximo ao VRM
- **Cabo**: Cabo EPS 12V de 8 pinos (4+4)
- **Função**: Alimentação do processador
- ⚠️ **IMPORTANTE**: DEVE estar conectado para o sistema funcionar

**3. Alimentação da Placa de Vídeo (GPU)**
- **XFX RX 9060 XT**: Requer 2x conectores PCIe 8 pinos (6+2) ou 1x conector PCIe 5.0 de 12 pinos
- **Cabo**: Use os cabos PCIe dedicados da fonte modular
- **Quantidade**: Verifique o manual da GPU, geralmente 2x 8 pinos ou 1x 16 pinos (12VHPWR)

**4. Alimentação dos Periféricos**
- **SSD M.2**: Não requer cabo de alimentação (alimentado pela placa-mãe)
- **SATA Drives**: Se adicionar no futuro, use cabos SATA power

---

### 5.6 CONEXÕES DO PAINEL FRONTAL (Front Panel)

#### F_PANEL (Conector 9 pinos 2x5)
**Localização**: Parte inferior direita da placa-mãe

**Pinagem do LIAN LI Vector V100:**

```
        PWR_LED+  PWR_LED-
HDD_LED+  HDD_LED-
PWR_BTN+  PWR_BTN-
RESET+    RESET-
        (vazio)   GND
```

**Conexões:**
- **PWRBTN (Power Button)**: Conectores PWR_BTN+ e PWR_BTN-
- **RESET (Reset Button)**: Conectores RESET+ e RESET-
- **PLED (Power LED)**: Conectores PWR_LED+ e PWR_LED-
- **HDD LED**: Conectores HDD_LED+ e HDD_LED-

⚠️ **NOTA**: Consulte o manual do gabinete e da placa para pinagem exata

---

### 5.7 CONEXÕES USB DO PAINEL FRONTAL

#### USB_3_1 (USB 3.2 Gen 1 - 19 pinos)
**Conectar**: Cabo USB 3.0/3.1 do painel frontal do gabinete
- **Localização**: Parte inferior direita da placa
- **Função**: Portas USB 3.0/3.1 frontais do gabinete

#### USB_C_1 (USB 3.2 Gen 2 Type-C)
**Conectar**: Cabo USB Type-C do painel frontal (se disponível no gabinete)
- **Localização**: Parte inferior da placa
- **Função**: Porta USB Type-C frontal

#### USB_4_5 (USB 2.0 - 9 pinos)
**Conectar**: Cabo USB 2.0 do painel frontal (se houver)
- **Localização**: Parte inferior da placa
- **Função**: Portas USB 2.0 frontais adicionais

---

### 5.8 CONEXÕES DE ÁUDIO

#### AAFP (Áudio Analógico do Painel Frontal - 9 pinos)
**Conectar**: Cabo de áudio HD do painel frontal do gabinete
- **Localização**: Parte inferior esquerda da placa
- **Função**: Saída de áudio e microfone frontais
- **Padrão**: HD Audio (High Definition Audio)

---

### 5.9 OUTRAS CONEXÕES

#### SATA_1 a SATA_4 (Conectores SATA 6Gb/s)
**Disponível para futuras expansões**:
- **Localização**: Lado direito da placa, próximo ao slot PCIe
- **Função**: Conexão de HDDs ou SSDs SATA adicionais
- **Cabos**: Use cabos SATA III incluídos com a placa-mãe

#### COM (Porta Serial - Header 9 pinos)
**Uso**: Opcional, para dispositivos seriais legados
- **Localização**: Parte inferior da placa
- **Função**: Não usado em builds modernos

---

## 6. DIAGRAMA VISUAL DE CONEXÕES

### Visão Superior da Placa-Mãe ASUS TUF GAMING B850M-PLUS

```
┌─────────────────────────────────────────────────────────────┐
│                    I/O Shield (Painel Traseiro)             │
│  [USB] [USB] [USB-C] [HDMI/DP] [LAN] [Audio Jacks]         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  [ATX_12V_2x4]     ┌─────────────┐                         │
│    (CPU Power)     │   Socket    │   [CPU_FAN] ← Bomba WC  │
│                    │    AM5      │   [CPU_OPT]             │
│                    │  Ryzen 7    │                         │
│                    │   7800X3D   │                         │
│  [DIMM_A1]         └─────────────┘                         │
│  [DIMM_A2] ← RAM 16GB                                      │
│  [DIMM_B1]                                                 │
│  [DIMM_B2]                    [ATX_24PIN]                  │
│                              (Main Power)                  │
│  [M.2_1] ← SSD Kingston NV3                                │
│                                                             │
│  ════════════════════════════════                          │
│  [PCIE_1] ← RX 9060 XT (x16)                               │
│  ────────────────────                                      │
│  [PCIE_2] (x4)                                             │
│  ────────                                                  │
│  [PCIE_3] (x1)                                             │
│                                                             │
│  [SATA_1][SATA_2]                                          │
│  [SATA_3][SATA_4]                                          │
│                                                             │
│  [USB_3_1] ← USB 3.0 Frontal                               │
│  [USB_C_1] ← USB-C Frontal (se houver)                     │
│  [USB_4_5] ← USB 2.0 Frontal                               │
│  [F_PANEL] ← Botões e LEDs frontais                        │
│  [AAFP] ← Áudio frontal                                    │
│  [CHA_FAN1] ← Ventiladores do radiador                     │
│  [CHA_FAN2] ← Exaustor traseiro                            │
│  [CHA_FAN3] ← 3x Ventiladores laterais                     │
│  [ADD_GEN2_1] ← ARGB Exaustor                              │
│  [ADD_GEN2_2] ← ARGB Laterais                              │
└─────────────────────────────────────────────────────────────┘
```

---

## 7. CONFIGURAÇÃO DOS VENTILADORES E FLUXO DE AR

### Layout dos Ventiladores no LIAN LI Vector V100

```
Vista Lateral do Gabinete:

FRENTE                                              TRASEIRA
  ↓                                                    ↑
┌────────────────────────────────────────────────────────┐
│ [Radiador]     ┌──────────────┐     [EXAUSTOR]       │
│  240mm WC      │ Componentes  │       120mm          │
│  (Intake)      │              │      (Exhaust)        │
│   ↓   ↓        │   Mobo       │         ↑            │
│                │   GPU        │                       │
│ [LATERAL]      │   PSU        │                       │
│  3x Fans       └──────────────┘                       │
│  (Reverse)                                            │
│  ↓   ↓   ↓                                           │
└────────────────────────────────────────────────────────┘
    ↓↓↓                                      ↑
  ENTRADA                                SAÍDA
```

### Configuração Recomendada:

1. **Radiador 240mm (Topo ou Frente)**: 
   - 2x ventiladores de 120mm em configuração INTAKE (puxando ar fresco)
   - Conectados em série ao cabo extensão PWM (K)
   - Cabo extensão conectado ao CHA_FAN1

2. **Ventilador Traseiro (Exaustor)**:
   - 1x ventilador 120mm em configuração EXHAUST (expelindo ar quente)
   - Conectado ao CHA_FAN2
   - Se tiver ARGB: conectado ao ADD_GEN2_1

3. **Ventiladores Laterais**:
   - 3x ventiladores em configuração REVERSE/INTAKE (puxando ar fresco)
   - Conectados a um hub/splitter PWM
   - Hub conectado ao CHA_FAN3
   - Se tiverem ARGB: hub ARGB conectado ao ADD_GEN2_2

**Pressão de Ar**: Positiva (mais entrada que saída)
- Entrada: 2 (radiador) + 3 (lateral) = 5 ventiladores
- Saída: 1 (traseiro) = 1 ventilador
- **Benefício**: Reduz acúmulo de poeira

---

## 8. INSTRUÇÕES DETALHADAS DE INSTALAÇÃO DO WATER COOLER

### Passo a Passo Completo:

#### 8.1 Instalação da Bomba (Conforme Manual)

1. **Preparação**:
   - Remova o cooler stock (se instalado)
   - Limpe o processador com álcool isopropílico
   - Deixe secar completamente

2. **Aplicação da Pasta Térmica**:
   - Se a bomba NÃO vier com pasta pré-aplicada:
     - Aplique uma quantidade do tamanho de um grão de arroz no centro da CPU
   - Se vier pré-aplicada:
     - Remova a proteção plástica da base da bomba

3. **Instalação do Suporte**:
   - Instale o backplate AM5 na parte traseira da placa-mãe
   - Fixe os espaçadores através dos orifícios

4. **Montagem da Bomba**:
   - Alinhe o suporte e a bomba sobre os parafusos dos espaçadores
   - Aperte as porcas de aperto manual (F) em padrão cruzado
   - **Sequência**: Canto superior esquerdo → Canto inferior direito → Canto superior direito → Canto inferior esquerdo
   - Repita o padrão cruzado até que todos os quatro cantos estejam firmemente apertados
   - **IMPORTANTE**: Não aperte um canto completamente antes dos outros

#### 8.2 Conexões do Water Cooler

1. **Bomba**:
   - Ligue o cabo PWM de 4 pinos da bomba ao conector **CPU_FAN** da placa-mãe
   - **Localização**: Próximo ao socket da CPU, parte superior esquerda

2. **Ventiladores do Radiador**:
   - As 2 ventoinhas do radiador vêm conectadas em série (daisy-chain)
   - Conecte o cabo principal das ventoinhas ao cabo de extensão PWM (K)
   - Ligue a outra extremidade do cabo de extensão ao conector **CHA_FAN1** da placa-mãe

3. **ARGB (se aplicável)**:
   - Se o Corsair Nautilus 240 RS tiver iluminação ARGB:
     - Conecte o cabo ARGB ao hub ARGB ou diretamente ao ADD_GEN2_2
   - Ou use o controlador RGB incluído (Corsair iCUE)

---

## 9. ORDEM DE MONTAGEM RECOMENDADA

### Sequência Ideal de Instalação:

1. ✅ **Instalar I/O Shield** na parte traseira do gabinete
2. ✅ **Instalar Backplate do Water Cooler** (antes de colocar a placa no gabinete)
3. ✅ **Instalar Processador (CPU)** no socket AM5
4. ✅ **Instalar Memória RAM** no slot DIMM_A2
5. ✅ **Instalar SSD M.2** no slot M.2_1
6. ✅ **Instalar a Bomba do Water Cooler** sobre a CPU
7. ✅ **Fixar a Placa-Mãe no gabinete** com espaçadores e parafusos
8. ✅ **Instalar a Placa de Vídeo** no slot PCIE_1
9. ✅ **Instalar o Radiador 240mm** no gabinete (topo ou frente)
10. ✅ **Instalar Ventiladores** (exaustor traseiro + 3 laterais)
11. ✅ **Conectar Cabos da Fonte** (ATX 24 pinos, EPS 8 pinos, PCIe GPU)
12. ✅ **Conectar Cabos da Bomba e Ventiladores** (PWM)
13. ✅ **Conectar Cabos ARGB**
14. ✅ **Conectar Painel Frontal** (botões, LEDs, USB, áudio)
15. ✅ **Organizar Cabos** com braçadeiras
16. ✅ **Fechar Gabinete**
17. ✅ **Conectar Periféricos Externos** (monitor, teclado, mouse)
18. ✅ **Ligar o Sistema** e verificar POST

---

## 10. CONFIGURAÇÕES DA BIOS (UEFI)

### Primeiro Boot - Verificações Importantes:

1. **Boot Priority**:
   - Pressione DEL ou F2 durante o POST
   - Configure o SSD Kingston NV3 como primeiro dispositivo de boot

2. **Configurações de RAM**:
   - Ative o perfil **EXPO** (AMD Extended Profiles for Overclocking)
   - Isso configurará a RAM para 6000MHz automaticamente
   - Caminho: AI Tweaker → Memory Frequency → EXPO

3. **Configurações dos Ventiladores**:
   - Configure as curvas de ventiladores em: Monitor → Fan Speed
   - **CPU_FAN** (Bomba): PWM Mode, Velocidade constante ~70-100%
   - **CHA_FAN1** (Radiador): PWM Mode, Curva baseada em temperatura da CPU
   - **CHA_FAN2** (Exaustor): PWM Mode, Curva baseada em temperatura do sistema
   - **CHA_FAN3** (Laterais): PWM Mode, Curva baseada em temperatura do sistema

4. **Configurações ARGB**:
   - Configure a iluminação via ASUS Aura Sync no Windows
   - Ou use o software Corsair iCUE para controle unificado

5. **PBO (Precision Boost Overdrive)**:
   - Pode ser ativado para melhor desempenho do Ryzen 7 7800X3D
   - Caminho: AI Tweaker → PBO → Advanced

6. **Resizable BAR**:
   - Ative para melhor performance da GPU
   - Caminho: Advanced → PCI Subsystem Settings → Re-Size BAR Support → Enabled

---

## 11. CHECKLIST FINAL DE CONEXÕES

### Antes de Ligar o Sistema:

- [ ] Processador instalado corretamente no socket AM5
- [ ] Memória RAM instalada no slot DIMM_A2 e travada
- [ ] SSD M.2 instalado no slot M.2_1 com dissipador térmico
- [ ] Bomba do water cooler instalada com pasta térmica
- [ ] Radiador 240mm fixado no gabinete
- [ ] Placa de vídeo instalada no slot PCIE_1 e fixada
- [ ] Cabo ATX 24 pinos conectado à placa-mãe
- [ ] Cabo EPS 8 pinos (CPU Power) conectado
- [ ] Cabos PCIe conectados à placa de vídeo
- [ ] Cabo PWM da bomba conectado ao CPU_FAN
- [ ] Cabo PWM dos ventiladores do radiador conectado ao CHA_FAN1
- [ ] Ventilador traseiro conectado ao CHA_FAN2
- [ ] Ventiladores laterais conectados ao CHA_FAN3 (via hub)
- [ ] Cabos ARGB conectados aos headers ADD_GEN2_1 e ADD_GEN2_2
- [ ] Cabos do painel frontal conectados (power, reset, LEDs)
- [ ] Cabo USB 3.0 frontal conectado
- [ ] Cabo de áudio frontal conectado
- [ ] Todos os cabos organizados e seguros
- [ ] Gabinete fechado
- [ ] Cabo de energia conectado à fonte
- [ ] Monitor conectado à placa de vídeo (NÃO à placa-mãe)
- [ ] Interruptor da fonte em posição "ON" (I)

---

## 12. SOLUÇÃO DE PROBLEMAS COMUNS

### Sistema Não Liga:

1. **Verifique**:
   - Cabo de energia conectado à fonte e tomada
   - Interruptor da fonte em "ON"
   - Cabos ATX 24 pinos e EPS 8 pinos bem conectados
   - Botão de power do painel frontal conectado corretamente

### Sistema Liga mas Não Dá Vídeo:

1. **Verifique**:
   - Monitor conectado à **placa de vídeo** (não à placa-mãe)
   - Placa de vídeo bem encaixada no slot
   - Cabos PCIe da GPU conectados
   - Memória RAM bem instalada e travada

### Temperaturas Altas da CPU:

1. **Verifique**:
   - Bomba do water cooler conectada ao CPU_FAN
   - Bomba funcionando (verifique RPM na BIOS)
   - Pasta térmica aplicada corretamente
   - Radiador com boa circulação de ar
   - Ventiladores do radiador funcionando

### Ventiladores Não Funcionam:

1. **Verifique**:
   - Conexões PWM nos headers corretos
   - Configurações de ventilador na BIOS
   - Se usar hub, verificar se o hub está alimentado

### RGB Não Funciona:

1. **Verifique**:
   - Cabos ARGB (3 pinos) conectados aos headers corretos
   - Não confundir ARGB (5V, 3 pinos) com RGB (12V, 4 pinos)
   - Software ASUS Aura Sync instalado no Windows

---

## 13. SOFTWARES RECOMENDADOS

### Para Monitoramento e Controle:

1. **ASUS Armoury Crate**:
   - Controle de RGB (Aura Sync)
   - Monitoramento de hardware
   - Atualização de BIOS e drivers

2. **AMD Ryzen Master**:
   - Monitoramento do processador
   - Controle de PBO e overclocking
   - Temperaturas e voltagens

3. **GPU-Z**:
   - Informações detalhadas da placa de vídeo
   - Monitoramento de frequências e temperaturas

4. **HWiNFO64**:
   - Monitoramento completo do sistema
   - Logs de sensores
   - Informações detalhadas de todos os componentes

5. **Corsair iCUE**:
   - Controle do water cooler Nautilus 240 RS
   - Monitoramento de temperaturas do líquido
   - Controle de ventiladores e RGB (se compatível)

---

## 14. ESPECIFICAÇÕES TÉCNICAS DA PLACA-MÃE

### ASUS TUF GAMING B850M-PLUS

**Formato**: Micro-ATX (mATX)
**Socket**: AMD AM5
**Chipset**: AMD B850

**Memória**:
- 4x DIMM DDR5 (até 256GB)
- Suporte a DDR5 6400MHz+ (OC)
- Dual Channel

**Slots de Expansão**:
- 1x PCIe 5.0 x16
- 1x PCIe 4.0 x4
- 1x PCIe 3.0 x1

**Armazenamento**:
- 2x M.2 (M.2_1: PCIe 5.0 x4, M.2_2: PCIe 4.0 x4)
- 4x SATA 6Gb/s

**USB (Painel Traseiro)**:
- USB 3.2 Gen 2 Type-C x1
- USB 3.2 Gen 2 Type-A x2
- USB 3.2 Gen 1 Type-A x4
- USB 2.0 x2

**Rede**:
- Intel 2.5Gb Ethernet

**Áudio**:
- Realtek ALC897/S1200A Codec
- 7.1 Surround Sound

**Alimentação**:
- 1x ATX 24 pinos
- 1x EPS 8 pinos (4+4)
- VRM: 10+2 fases

---

## 15. GARANTIAS E SUPORTE

### Informações de Garantia:

- **Processador AMD**: 3 anos
- **Placa de Vídeo XFX**: 2 anos
- **SSD Kingston**: 5 anos
- **Memória Kingston**: Garantia vitalícia
- **Placa-Mãe ASUS**: 3 anos
- **Water Cooler Corsair**: 2 anos
- **Fonte Pichau**: Verifique com o fabricante

### Links de Suporte:

- **ASUS**: https://www.asus.com/br/support/
- **AMD**: https://www.amd.com/pt/support
- **Corsair**: https://www.corsair.com/br/pt/suporte

---

## 16. MANUTENÇÃO RECOMENDADA

### A Cada 3 Meses:
- Limpeza de poeira com ar comprimido
- Verificação de temperaturas
- Atualização de drivers

### A Cada 6 Meses:
- Verificação de firmwares
- Limpeza profunda dos filtros de ar
- Verificação de cabos soltos

### A Cada 2 Anos:
- Troca de pasta térmica (se necessário)
- Verificação do líquido do water cooler (coolers AIO são selados, apenas verificar ruídos)

---

## CONCLUSÃO

Este mapa de conexão fornece todas as informações necessárias para montar e conectar corretamente todos os componentes do seu PC baseado na placa-mãe ASUS TUF GAMING B850M-PLUS.

**Pontos Críticos a Lembrar**:
1. ✅ Bomba do water cooler SEMPRE no CPU_FAN
2. ✅ Ventiladores do radiador em série + cabo extensão → CHA_FAN1
3. ✅ GPU no primeiro slot PCIe x16
4. ✅ RAM no slot DIMM_A2 (ou A2+B2 para dual-channel)
5. ✅ Monitor conectado à GPU, não à placa-mãe
6. ✅ ARGB são 3 pinos (5V), não confundir com RGB 4 pinos (12V)
7. ✅ Fluxo de ar: Positivo (mais entrada que saída)

**Em caso de dúvidas**: Sempre consulte os manuais dos componentes ou entre em contato com o suporte técnico dos fabricantes.

---

**Documento criado**: Fevereiro 2026  
**Versão**: 1.0  
**Plataforma**: ASUS TUF GAMING B850M-PLUS (AMD AM5)

---

*Este documento foi elaborado com base nas especificações técnicas dos componentes listados. Sempre consulte os manuais oficiais dos fabricantes para informações específicas e atualizadas.*
