# Estrutura e Arquitetura de Sistemas Operacionais  
## Atividade – Sistemas Operacionais Baseados em Outros

## 1. Introdução

Muitos sistemas operacionais modernos não são desenvolvidos completamente do zero. Em vez disso, utilizam como base sistemas já existentes, reaproveitando principalmente o **kernel**, a **arquitetura do sistema** ou a **estrutura de gerenciamento de recursos**.

Essa prática é comum porque permite:

- Reduzir o tempo de desenvolvimento  
- Aproveitar tecnologias já testadas e estáveis  
- Melhorar compatibilidade com hardware  
- Facilitar manutenção e atualizações

A seguir estão exemplos de sistemas operacionais que utilizam outros sistemas como base.

---

# 2. Sistemas Operacionais

## Ubuntu

<div style="display: flex; justify-content: center">
<img src= "https://upload.wikimedia.org/wikipedia/commons/a/ab/Logo-ubuntu_cof-orange-hex.svg" width= 250>
</div>

- **Sistema Operacional:** Ubuntu  
- **Sistema Base:** Debian  
- **Tipo de Kernel:** Linux 
<div style="display: flex; justify-content: center"> 
<img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Desktop_Ubuntu_20.04.png" width=320>
</div>

- **Principais Características:**  
  - Distribuição Linux popular para desktops e servidores  
  - Interface amigável e fácil de usar  
  - Grande comunidade e suporte de software  
- **Principais Diferenças em relação ao sistema base:**  
  - Interface gráfica própria e otimizada  
  - Atualizações mais frequentes  
  - Foco maior em usuários domésticos e iniciantes

---

## macOS

<div style="display: flex; justify-content: center">
<img src= "https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" width= 250>
</div>

- **Sistema Operacional:** macOS  
- **Sistema Base:** Unix / BSD (Darwin)  
- **Tipo de Kernel:** XNU (kernel híbrido baseado em Mach + BSD)
<div style="display: flex; justify-content: center"> 
<img src="https://www.pngall.com/wp-content/uploads/20/iPhone-17-Pro-Max-Concept-Art-PNG.png" width=320>
</div>
  
- **Principais Características:**  
  - Sistema operacional desenvolvido pela Apple  
  - Interface gráfica própria e altamente integrada  
  - Forte integração entre hardware e software  
- **Principais Diferenças em relação ao sistema base:**  
  - Interface gráfica exclusiva da Apple  
  - Diversas ferramentas e APIs proprietárias  
  - Otimização específica para computadores Mac

---

## Android

<div style="display: flex; justify-content: center">
<img src= "https://upload.wikimedia.org/wikipedia/commons/d/d7/Android_robot.svg" width= 250>
</div>

- **Sistema Operacional:** Android  
- **Sistema Base:** Linux  
- **Tipo de Kernel:** Linux modificado  
- **Principais Características:**  
  - Sistema operacional voltado para smartphones e tablets  
  - Suporte a sensores, telas touchscreen e conectividade móvel  
  - Grande ecossistema de aplicativos  
- **Principais Diferenças em relação ao sistema base:**  
  - Kernel Linux adaptado para dispositivos móveis  
  - Interface gráfica própria para telas touch  
  - Camadas adicionais como Android Runtime e framework de apps

---

## Xbox 360

<div style="display: flex; justify-content: center">
<img src= "https://cdn.worldvectorlogo.com/logos/xbox-360-1.svg" width= 250>
</div>

- **Sistema Operacional:** Xbox 360 OS  
- **Sistema Base:** Windows NT (adaptado)  
- **Tipo de Kernel:** Kernel personalizado derivado do NT  
  <div style= "display: flex; justify-content: center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Xbox_360_Models.png" width=300>
  </div>
- **Principais Características:**  
  - Sistema desenvolvido pela Microsoft para o console Xbox 360  
  - Otimizado para jogos e multimídia  
  - Interface conhecida como **Xbox Dashboard**  
- **Principais Diferenças em relação ao sistema base:**  
  - Remoção de componentes de desktop do Windows  
  - Sistema altamente otimizado para hardware do console  
  - Interface voltada exclusivamente para entretenimento

---

## Xbox One / Xbox Series

<div style="display: flex; justify-content: center; gap: 35px">
<img src= "https://www.svgrepo.com/show/303136/xbox-one-logo.svg" width= 250>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/af/Xbox_Series_X_logo.svg/3840px-Xbox_Series_X_logo.svg.png" width= 250>
</div>

- **Sistema Operacional:** Xbox OS  
- **Sistema Base:** Windows 10 (Windows NT)  
- **Tipo de Kernel:** Windows NT modificado
<div style="display: flex; justify-content: center"> 
<img src="https://t.ctcdn.com.br/vIV8mcgB4lNpVZioboFqUC_kBMk=/fit-in/600x600/filters:fill(transparent):watermark(wm/prd.png,-32p,center,1,none,15)/i413842.png" width=250>
</div>

- **Principais Características:**  
  - Sistema utilizado nos consoles Xbox One e Xbox Series X/S  
  - Arquitetura baseada em múltiplos sistemas virtuais  
  - Integração com o ecossistema Windows e serviços da Microsoft  
- **Principais Diferenças em relação ao sistema base:**  
  - Uso de máquinas virtuais separando sistema, apps e jogos  
  - Interface otimizada para controle e TV  
  - Recursos específicos para jogos e streaming

---

# 3. Conclusão

A reutilização da base de sistemas operacionais é uma prática comum na indústria de tecnologia. Utilizar sistemas já existentes como base permite que empresas aproveitem tecnologias consolidadas, reduzam custos de desenvolvimento e aumentem a estabilidade do sistema.

Essa estratégia é utilizada em diferentes áreas da computação, desde **computadores pessoais**, como no caso do macOS e Ubuntu, até **dispositivos móveis**, como o Android, e **consoles de videogame**, como os sistemas utilizados nos consoles Xbox.

---

# 4. Referências

- TANENBAUM, Andrew S.; BOS, Herbert. **Sistemas Operacionais Modernos**.  
- SILBERSCHATZ, Abraham; GALVIN, Peter B.; GAGNE, Greg. **Fundamentos de Sistemas Operacionais**.  
- Documentação oficial do Linux Kernel – https://www.kernel.org  
- Android Open Source Project – https://source.android.com  
- Apple Developer Documentation – https://developer.apple.com  
- Microsoft Developer Documentation – https://learn.microsoft.com  