<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Montar PC</title>
<style>
  body { font-family: Arial, sans-serif; padding: 20px; }
  label { display: block; margin-top: 10px; }
  select, button { width: 320px; padding: 5px; margin-top: 5px; }
  #total { margin-top: 20px; font-size: 1.2em; font-weight: bold; }
  #resumo { margin-top: 20px; padding: 10px; border: 1px solid #ccc; white-space: pre-wrap; }
  #linkPartilha { margin-top: 10px; word-break: break-all; }
</style>
</head>
<body>
  <h1>Montar o Meu PC</h1>

  <label for="cpu">CPU:</label>
  <select id="cpu" name="cpu">
    <option value="0">-- Escolhe CPU --</option>
    <option value="220">AMD Ryzen 5 5600X - 220€</option>
    <option value="350">AMD Ryzen 7 5800X - 350€</option>
    <option value="400">Intel i5-12600K - 400€</option>
    <option value="550">Intel i7-12700K - 550€</option>
    <option value="700">Intel i9-12900K - 700€</option>
    <option value="300">AMD Ryzen 9 5900X - 300€</option>
    <option value="150">AMD Ryzen 3 3100 - 150€</option>
    <option value="100">Intel i3-10100 - 100€</option>
    <option value="180">AMD Ryzen 5 3600 - 180€</option>
    <option value="320">Intel i5-11400F - 320€</option>
  </select>

  <label for="gpu">GPU:</label>
  <select id="gpu" name="gpu">
    <option value="0">-- Escolhe GPU --</option>
    <option value="400">NVIDIA RTX 3060 - 400€</option>
    <option value="700">NVIDIA RTX 3070 - 700€</option>
    <option value="1200">NVIDIA RTX 3080 - 1200€</option>
    <option value="1500">NVIDIA RTX 3090 - 1500€</option>
    <option value="250">AMD RX 6600 XT - 250€</option>
    <option value="450">AMD RX 6700 XT - 450€</option>
    <option value="600">AMD RX 6800 XT - 600€</option>
    <option value="900">NVIDIA RTX 4080 - 900€</option>
    <option value="1300">NVIDIA RTX 4090 - 1300€</option>
    <option value="350">NVIDIA GTX 1660 Super - 350€</option>
  </select>

  <label for="ram">RAM:</label>
  <select id="ram" name="ram">
    <option value="0">-- Escolhe RAM --</option>
    <option value="50">16GB DDR4 3200MHz - 50€</option>
    <option value="90">32GB DDR4 3200MHz - 90€</option>
    <option value="70">16GB DDR4 3600MHz - 70€</option>
    <option value="130">32GB DDR4 3600MHz - 130€</option>
    <option value="45">8GB DDR4 3000MHz - 45€</option>
    <option value="110">64GB DDR4 3200MHz - 110€</option>
    <option value="60">16GB DDR5 4800MHz - 60€</option>
    <option value="100">32GB DDR5 4800MHz - 100€</option>
    <option value="120">64GB DDR5 4800MHz - 120€</option>
    <option value="30">8GB DDR5 4800MHz - 30€</option>
  </select>

  <label for="armazenamento">Armazenamento:</label>
  <select id="armazenamento" name="armazenamento">
    <option value="0">-- Escolhe Armazenamento --</option>
    <option value="50">SSD 500GB NVMe - 50€</option>
    <option value="80">SSD 1TB NVMe - 80€</option>
    <option value="120">SSD 2TB NVMe - 120€</option>
    <option value="40">HDD 1TB 7200RPM - 40€</option>
    <option value="70">HDD 2TB 7200RPM - 70€</option>
    <option value="150">SSD 4TB NVMe - 150€</option>
    <option value="90">SSD 1TB SATA - 90€</option>
    <option value="130">SSD 2TB SATA - 130€</option>
    <option value="60">HDD 500GB 7200RPM - 60€</option>
    <option value="100">SSD 3TB NVMe - 100€</option>
  </select>

  <label for="motherboard">Motherboard:</label>
  <select id="motherboard" name="motherboard">
    <option value="0">-- Escolhe Motherboard --</option>
    <option value="120">MSI B550 Tomahawk - 120€</option>
    <option value="200">ASUS ROG Strix X570 - 200€</option>
    <option value="150">Gigabyte B660 Aorus - 150€</option>
    <option value="170">ASRock X570 Taichi - 170€</option>
    <option value="130">MSI Z690 Pro - 130€</option>
    <option value="100">ASUS Prime B560 - 100€</option>
    <option value="80">Gigabyte B450M DS3H - 80€</option>
    <option value="210">ASUS ROG Crosshair VIII - 210€</option>
    <option value="140">MSI MAG B660 - 140€</option>
    <option value="190">ASRock Z690 Steel Legend - 190€</option>
  </select>

  <label for="caixa">Caixa:</label>
  <select id="caixa" name="caixa">
    <option value="0">-- Escolhe Caixa --</option>
    <option value="70">NZXT H510 - 70€</option>
    <option value="80">Corsair 4000D - 80€</option>
    <option value="60">Cooler Master MasterBox - 60€</option>
    <option value="90">Fractal Design Meshify C - 90€</option>
    <option value="50">Phanteks Eclipse P300 - 50€</option>
    <option value="100">Lian Li PC-O11 Dynamic - 100€</option>
    <option value="65">be quiet! Pure Base 500 - 65€</option>
    <option value="85">Thermaltake V200 - 85€</option>
    <option value="55">Cooler Master NR600 - 55€</option>
    <option value="75">Corsair Crystal 280X - 75€</option>
  </select>

  <label for="fonte">Fonte:</label>
  <select id="fonte" name="fonte">
    <option value="0">-- Escolhe Fonte --</option>
    <option value="60">Corsair CX550M 550W - 60€</option>
    <option value="90">EVGA SuperNOVA 650 G5 - 90€</option>
    <option value="120">Seasonic Focus GX-750 - 120€</option>
    <option value="80">Cooler Master MWE Gold 650W - 80€</option>
    <option value="100">Corsair RM750x - 100€</option>
    <option value="70">Thermaltake Smart 600W - 70€</option>
    <option value="110">be quiet! Straight Power 11 750W - 110€</option>
    <option value="95">NZXT C750 - 95€</option>
    <option value="85">Cooler Master V750 - 85€</option>
    <option value="130">Seasonic Prime TX-850 - 130€</option>
  </select>

  <label for="cooler">Cooler:</label>
  <select id="cooler" name="cooler">
    <option value="0">-- Escolhe Cooler --</option>
    <option value="25">Cooler stock AMD - 25€</option>
    <option value="30">Cooler stock Intel - 30€</option>
    <option value="45">Cooler Master Hyper 212 - 45€</option>
    <option value="60">be quiet! Pure Rock 2 - 60€</option>
    <option value="70">Noctua NH-U12S - 70€</option>
    <option value="90">ARCTIC Freezer 34 eSports - 90€</option>
    <option value="100">Noctua NH-D15 - 100€</option>
    <option value="110">Corsair H60 (líquido) - 110€</option>
    <option value="130">NZXT Kraken X53 - 130€</option>
    <option value="150">Corsair iCUE H100i Elite Capellix - 150€</option>
    <option value="180">Cooler Master MasterLiquid ML360 - 180€</option>
  </select>

  <label for="loja">Escolhe a região da loja:</label>
  <select id="loja" name="loja">
    <option value="">-- Escolhe --</option>
    <option value="https://www.pcdiga.com">Península Ibérica (PCDiga)</option>
    <option value="https://www.globaldata.pt">Península Ibérica (Globaldata)</option>
    <option value="https://www.alternate.eu">Europa (Alternate.eu)</option>
    <option value="https://www.caseking.de">Europa (Caseking)</option>
  </select>

  <div id="total">Preço Total: 0€</div>

  <button onclick="mostrarResumo()">Mostrar Resumo e Ir à Loja</button>
  <button onclick="guardarPDF()">Guardar como PDF</button>
  <button onclick="gerarLink()">Gerar Link Partilhável</button>

  <div id="resumo"></div>
  <div id="linkPartilha"></div>

<script>
  const selects = document.querySelectorAll('select');
  const totalDiv = document.getElementById('total');
  const resumoDiv = document.getElementById('resumo');
  const lojaSelect = document.getElementById('loja');
  const linkPartilhaDiv = document.getElementById('linkPartilha');

  // Calcula total do preço
  function calcularTotal() {
    let total = 0;
    selects.forEach(select => {
      if (select.value && select.id !== 'loja') {
        total += parseInt(select.value);
      }
    });
    totalDiv.textContent = `Preço Total: ${total}€`;
  }

  // Mostrar resumo e link para loja
  function mostrarResumo() {
    let texto = 'Componentes Escolhidos:\n';
    selects.forEach(select => {
      if (select.id !== 'loja' && select.selectedIndex > 0) {
        texto += `- ${select.options[select.selectedIndex].text}\n`;
      }
    });
    const loja = lojaSelect.value;
    if (loja) {
      texto += `\nLoja: ${loja}\n`;
      texto += 'Clica no botão abaixo para ir à loja.\n';
      resumoDiv.innerHTML = texto.replace(/\n/g, '<br>');
      resumoDiv.innerHTML += `<br><button onclick="window.open('${loja}','_blank')">Ir para a Loja</button>`;
    } else {
      resumoDiv.innerHTML = texto.replace(/\n/g, '<br>') + '<br><span style="color:red;">Seleciona uma região de loja para continuar.</span>';
    }
  }

  // Guardar resumo como PDF (usa impressão do browser)
  function guardarPDF() {
    const resumo = resumoDiv.innerHTML;
    if (!resumo) {
      alert('Mostra o resumo primeiro!');
      return;
    }
    const janela = window.open('', '', 'height=600,width=800');
    janela.document.write('<html><head><title>Resumo do PC</title></head><body>');
    janela.document.write('<h1>Resumo do PC Escolhido</h1>');
    janela.document.write(resumo);
    janela.document.write('</body></html>');
    janela.document.close();
    janela.print();
  }

  // Gerar link com parâmetros na URL
  function gerarLink() {
    const params = new URLSearchParams();
    selects.forEach(select => {
      if (select.value && select.value !== '0') {
        params.set(select.id, select.value);
      }
    });
    const url = `${location.origin}${location.pathname}?${params.toString()}`;
    linkPartilhaDiv.innerHTML = `Link partilhável:<br><a href="${url}" target="_blank">${url}</a>`;
  }

  // Preenche selects lendo URL
  function preencherComURL() {
    const params = new URLSearchParams(window.location.search);
    let changed = false;
    selects.forEach(select => {
      if (params.has(select.id)) {
        const val = params.get(select.id);
        for (let i=0; i < select.options.length; i++) {
          if (select.options[i].value === val) {
            select.selectedIndex = i;
            changed = true;
            break;
          }
        }
      }
    });
    if (changed) {
      calcularTotal();
      mostrarResumo();
    }
  }

  // Event listeners para recalcular
  selects.forEach(select => {
    select.addEventListener('change', () => {
      calcularTotal();
      resumoDiv.innerHTML = '';
      linkPartilhaDiv.innerHTML = '';
    });
  });

  // Ao abrir página
  window.onload = () => {
    preencherComURL();
    calcularTotal();
  };
</script>
</body>
</html>
