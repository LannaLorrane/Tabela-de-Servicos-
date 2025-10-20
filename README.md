<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tabela de Serviços - Pintura Hidro Arts</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #ffffff;
      color: #000;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #66b2ff;
      padding: 15px;
      text-align: center;
    }

    header h1 {
      color: #ffffff;
      font-size: 1.8em;
      margin: 0;
    }

    header h2 {
      color: #0056b3;
      font-size: 1.1em;
      font-weight: 700;
      margin-top: 3px;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 15px 5px;
      max-width: 100%;
      margin: auto;
    }

    .servico {
      background-color: #fff;
      border: 2px solid #007bff;
      border-radius: 10px;
      padding: 10px;
      margin-bottom: 10px;
      width: 100%;
      box-sizing: border-box;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .servico:hover {
      transform: translateY(-3px);
      box-shadow: 3px 3px 5px rgba(86, 154, 223, 0.8);
    }

    .servico h3 {
      color: #0056b3;
      font-size: 1.05em;
      margin-bottom: 4px;
    }

    .servico p, .servico ul {
      font-size: 1.1em; /* maior para leitura confortável */
      line-height: 1.6;
      color: #333;
      text-align: justify;
    }

    .servico ul {
      padding-left: 15px;
    }

    .observacao {
      text-align: center;
      margin: 15px 0;
      font-size: 0.9em;
      color: #555;
    }

    footer {
      text-align: center;
      background-color: #66b2ff;
      color: white;
      padding: 12px;
      margin-top: 20px;
      font-size: 0.9em;
    }

    footer a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    footer a:hover {
      text-decoration: underline;
    }

    /* Responsividade extra para telas pequenas */
    @media (max-width: 500px) {
      .servico {
        padding: 8px;
      }
      .servico h3 {
        font-size: 1em;
      }
      .servico p, .servico ul {
        font-size: 1em; /* maior no celular também */
        line-height: 1.5;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>TABELA DE SERVIÇOS</h1>
    <h2>PINTURA HIDRO ARTS</h2>
  </header>

  <div class="container">
    <!-- Blocos de serviços (29) -->
    <div class="servico">
      <h3>Lavagem Simples</h3>
      <p>Limpeza com luva e pano de microfibra, pré-lavagem para evitar riscos, shampoo automotivo, pretinho nos pneus, aspiração interna com limpeza bactericida e cheirinho. Deixa o carro limpo, higienizado e com brilho renovado.</p>
    </div>
    <div class="servico">
      <h3>Lavagem Técnica</h3>
      <p>Inclui pré-lavagem, shampoo automotivo, limpeza detalhada de pneus, descontaminação ferrosa, aspiração interna com limpeza bactericida, revitalização e hidratação dos plásticos, e cera de proteção de três meses.</p>
    </div>
    <div class="servico">
      <h3>Higienização Simples</h3>
      <p>Limpeza interna detalhada com escovação de bancos, painel, teto, carpete e portas, usando produto antibactericida e aspirador. Não desmonta o carro. Finaliza com aromatizante, deixando o interior limpo e saudável.</p>
    </div>
    <div class="servico">
      <h3>Higienização Plus</h3>
      <p>Limpeza completa interna com escovação, aspirador, desmontagem interna do carro, proteção dos plásticos e uso de vapor para eliminar fungos, bactérias e odores, finalizando com aromatizante.</p>
    </div>
    <div class="servico">
      <h3>Higienização de Motor</h3>
      <p>Limpeza detalhada do motor com aplicação de verniz de proteção.</p>
    </div>
    <div class="servico">
      <h3>Higienização Interna do Carro, Parte por Parte</h3>
      <ul>
        <li><strong>Teto:</strong> limpeza detalhada</li>
        <li><strong>Carpete:</strong> limpeza detalhada ou removendo o carpete</li>
        <li><strong>Plásticos:</strong> portas, colunas e painel</li>
        <li><strong>Bancos:</strong> motorista e passageiros</li>
      </ul>
    </div>
    <div class="servico">
      <h3>Higienização de Rodas</h3>
      <p>Limpeza detalhada das rodas, removendo sujeira e resíduos acumulados.</p>
    </div>
    <div class="servico">
      <h3>Pretinho</h3>
      <p>Aplicação de pretinho nos pneus, com remoção de graxa ou lama pesada quando necessário, proporcionando acabamento limpo e visual renovado.</p>
    </div>
    <div class="servico">
      <h3>Micro Pintura</h3>
      <p>Retoque pontual de pintura em pequenas áreas, ideal para eliminar riscos leves ou manchas sem precisar repintar a peça inteira, preservando o acabamento original.</p>
    </div>
    <div class="servico">
      <h3>Pintura Completa Carro + Polimento</h3>
      <p>Serviço completo de pintura de carro, portas, para-lamas, para-choques, capô, teto, porta-malas e peças internas, incluindo polimento para uniformidade e acabamento de alta qualidade.</p>
    </div>
    <div class="servico">
      <h3>Restauração de Plástico</h3>
      <p>Limpeza e descontaminação de plásticos internos e externos, aplicação de produto restaurador e vitrificação, garantindo proteção e renovação por um ano.</p>
    </div>
    <div class="servico">
      <h3>Restauração de Vidros</h3>
      <p>Limpeza completa de todos os vidros com descontaminador de chuva ácida, proteção e acabamento interno e externo.</p>
    </div>
    <div class="servico">
      <h3>Pintura de Rodas (Caminhão, Carretas)</h3>
      <p>Pintura completa ou parcial das rodas, incluindo aro, cubo e personalizações, podendo restaurar o padrão original ou aplicar cores personalizadas, garantindo acabamento uniforme, proteção e aparência profissional.</p>
    </div>
    <div class="servico">
      <h3>Vitrificação de Farol</h3>
      <p>Polimento da lente e aplicação de proteção vitrificante, garantindo durabilidade e proteção de um ano.</p>
    </div>
    <div class="servico">
      <h3>Restauração de Farol</h3>
      <p>Lixamento progressivo da lente, isolamento e aplicação de proteção vitrificante, com garantia de um ano.</p>
    </div>
    <div class="servico">
      <h3>Restauração de Farol com Polimento</h3>
      <p>Lixamento progressivo e polimento do farol, isolamento e aplicação de polímero, com três anos de proteção.</p>
    </div>
    <div class="servico">
      <h3>Polimento de Rapatema (Casca de Laranja)</h3>
      <p>Lixamento progressivo, polimento técnico de todas as chapas, isolamento das borrachas e aplicação de selante com proteção de um ano, lavagem simples incluída.</p>
    </div>
    <div class="servico">
      <h3>Polimento Tanques</h3>
      <p>Polimento completo de tanques usando máquina e, quando necessário, Bombril, garantindo superfícies limpas e uniformes. Também é possível aplicar pintura de cinta no tanque.</p>
    </div>
    <div class="servico">
      <h3>Polimento Espelhado Fora do Lugar</h3>
      <p>Tratamento de desgaste do alumínio com máquina, realizado fora da posição original do tanque, proporcionando acabamento espelhado e superfície uniforme.</p>
    </div>
    <div class="servico">
      <h3>Polimento Espelhado no Lugar</h3>
      <p>Desgaste do alumínio tratado com máquina, mantendo o tanque no local, ideal para recuperação de brilho sem remoção da peça.</p>
    </div>
    <div class="servico">
      <h3>Polimento Caminhão</h3>
      <p>Acabamento de superfícies de caminhões, incluindo lixamento quando necessário, aplicação de cera e polimento de áreas foscas, garantindo brilho uniforme e renovação da pintura.</p>
    </div>
    <div class="servico">
      <h3>Polimento Alumínio</h3>
      <p>Polimento detalhado de suportes de alumínio, tampas de mala e descarga, usando máquina, lixamento ou Bombril conforme a necessidade, garantindo acabamento liso e brilho uniforme.</p>
    </div>
    <div class="servico">
      <h3>Polimento Rodas Alumínio</h3>
      <p>Polimento das rodas com máquina, à mão ou usando Bombril e lixa, incluindo restauração da roda espelhada, proporcionando brilho, proteção e aparência renovada.</p>
    </div>
    <div class="servico">
      <h3>Polimento Carreta</h3>
      <p>Polimento completo de carretas, cobrindo tetos altos e baixos, bicudas e novas superfícies. Inclui lixamento quando necessário e aplicação de cera, garantindo brilho uniforme e renovação da pintura.</p>
    </div>
    <div class="servico">
      <h3>Polimento Comercial One Step</h3>
      <p>Lavagem, descontaminação com clay bar, polimento de uma etapa que remove 50% dos riscos, e aplicação de hidrorepelente com proteção de seis meses.</p>
    </div>
    <div class="servico">
      <h3>Polimento Comercial Silitização</h3>
      <p>Lavagem, descontaminação com clay bar, polimento de uma etapa removendo 50% dos riscos, proteção com hidrorepelente de um ano e isolamento das borrachas.</p>
    </div>
    <div class="servico">
      <h3>Polimento Técnico e Vitrificação</h3>
      <p>Lavagem simples, descontaminação, polimento em três etapas removendo 100% dos riscos, lixamento para arranhões profundos, isolamento de borrachas e vidros, e vitrificação com proteção de um ano.</p>
    </div>
    <div class="servico">
      <h3>Polimento Técnico e Vitrificação PRO 9H3Y</h3>
      <p>Lavagem técnica, descontaminação, polimento em três etapas com remoção total de riscos, lixamento profundo, isolamento e vitrificação com proteção de três anos.</p>
    </div>
    <div class="servico">
      <h3>Polimento Técnico e Vitrificação PRO 9H5Y</h3>
      <p>Lavagem técnica, descontaminação de vidros e pintura, polimento em três etapas, detalhamento das partes pequenas, lixamento de arranhões profundos, isolamento e vitrificação com proteção de três anos, finalizando com lavagem de motor ou vitrificação de farol.</p>
    </div>

    <div class="observacao">
      Todas as informações citadas neste site são verdadeiras, mas para saber mais detalhes sobre cada serviço, consulte um de nós diretamente: pessoalmente, via Direct ou WhatsApp.
    </div>

  </div>

  <footer>
    <p>© 2025 <a href="https://www.instagram.com/pintura_hidro_arts?igsh=MTZiNTl5MXlzeTMw" target="_blank">Instagram Pintura Hidro Arts</a></p>
  </footer>

</body>
</html>
