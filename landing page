<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🚨 Guia de Segurança Digital: Proteja-se de Golpes 🚨</title>
    <style>
        * { box-sizing: border-box; }
        body {
            font-family: system-ui, -apple-system, sans-serif;
            font-size: 1.5rem;
            background: #1a1a1a;
            color: #ffffff;
            line-height: 1.6;
            margin: 0;
            padding: 2rem;
        }
        header { text-align: center; margin-bottom: 3rem; }
        h1 { font-size: 3rem; margin: 0; color: #ff4444; }
        h2 { font-size: 2.5rem; border-bottom: 3px solid #ff4444; padding-bottom: 0.5rem; margin-top: 3rem; }
        h3 { font-size: 2rem; color: #ffdd44; margin-top: 0; }
        
        .card {
            background: #333333;
            padding: 2rem;
            border-radius: 15px;
            margin-bottom: 2rem;
            border-left: 5px solid #ff4444;
            box-shadow: 0 8px 16px rgba(0,0,0,0.5);
        }

        .example-box {
            background: #ff4444;
            color: #ffffff;
            padding: 1.5rem;
            border-radius: 10px;
            font-style: italic;
            font-weight: bold;
            border-left: 5px solid #ffffff;
            margin: 1rem 0;
        }

        .btn-interativo {
            background: #ffdd44;
            color: #000;
            border: none;
            padding: 1.2rem 2rem;
            font-size: 1.5rem;
            font-weight: bold;
            border-radius: 10px;
            cursor: pointer;
            margin: 10px 5px;
            transition: transform 0.2s;
        }
        .btn-interativo:active { transform: scale(0.95); }

        .perigo-destaque { color: #ff4444; font-weight: bold; text-decoration: underline; background-color: rgba(255, 68, 68, 0.1); padding: 2px 5px; }
        .feedback { font-weight: bold; margin-top: 15px; font-size: 1.8rem; }
        
        input[type="checkbox"] { transform: scale(2.2); margin-right: 20px; cursor: pointer; }
        label { cursor: pointer; display: inline-block; margin-bottom: 15px; }

        strong { color: #ff4444; }

        /* Estilo para os links de fontes */
        .link-fonte {
            color: #ffdd44;
            text-decoration: none;
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        .link-fonte:hover { text-decoration: underline; color: #ffffff; }

        @media (max-width: 768px) {
            body { padding: 1rem; font-size: 1.2rem; }
            h1 { font-size: 2.2rem; }
            h2 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>🚨 ALERTA: Proteja-se de Golpes! 🚨</h1>
        <p>Um guia simples para você navegar com segurança e tranquilidade.</p>
    </header>

    <main>
        <!-- SEÇÃO: 5 REGRAS DE OURO -->
        <section id="regras">
            <h2>🏆 5 Regras de Ouro da Proteção</h2>
            <div class="card">
                <ol>
                    <li><strong>Desconfie de urgências:</strong> Golpistas sempre dizem que "precisa ser agora".</li>
                    <li><strong>Nunca dê senhas:</strong> Nem para o banco, nem para parentes por mensagem.</li>
                    <li><strong>Ligue para confirmar:</strong> Se um parente pedir dinheiro, ligue para o número antigo dele.</li>
                    <li><strong>Bancos não pedem Pix:</strong> Funcionários do banco nunca ligam pedindo transferência.</li>
                    <li><strong>Peça ajuda:</strong> Na dúvida, não clique em nada e chame alguém de confiança.</li>
                </ol>
            </div>
        </section>

        <!-- SEÇÃO: WHATSAPP -->
        <section id="whatsapp">
            <h2>📱 Golpe no WhatsApp</h2>
            <div class="card">
                <h3>Como eles fazem?</h3>
                <p>Usam uma <strong>foto sua ou de um parente</strong> em um número novo e fingem que o celular quebrou para pedir dinheiro urgente.</p>
                <div class="example-box">
                    "Oi mãe, troquei de número! Salva aí. Preciso pagar uma conta urgente e meu app travou, consegue fazer um Pix pra mim?"
                </div>
                <p><strong>Dica:</strong> Bloqueie imediatamente e denuncie o contato.</p>
            </div>
        </section>

        <!-- SEÇÃO: PIX -->
        <section id="pix">
            <h2>💰 Golpe no Pix</h2>
            <div class="card">
                <h3>Falsa Central e Pix por Engano</h3>
                <p>Eles ligam fingindo ser do banco ou dizem que mandaram um "Pix errado" para você e pedem que você devolva para uma conta diferente.</p>
                <p><strong>Lembre-se:</strong> Se recebeu um Pix por engano, use a função "Devolver" dentro do próprio aplicativo do seu banco.</p>
            </div>
        </section>

        <!-- SEÇÃO INTERATIVA: QUIZ -->
        <section class="card">
            <h2>🧠 Desafio de Segurança</h2>
            <p>O banco ligou dizendo que sua conta foi hackeada e pede para você transferir seu dinheiro para uma "conta segura". Você faz isso?</p>
            <button class="btn-interativo" onclick="responderQuiz(true)">SIM, EU FAÇO</button>
            <button class="btn-interativo" onclick="responderQuiz(false)">NÃO, É GOLPE</button>
            <p id="feedback-quiz" class="feedback"></p>
        </section>

        <!-- SEÇÃO INTERATIVA: SIMULADOR -->
        <section class="card">
            <h2>🔍 Detetive Digital</h2>
            <p>Clique no botão abaixo para analisar esta mensagem suspeita:</p>
            <div id="caixa-simulador" style="padding: 15px; border: 2px dashed #666; margin-bottom: 15px;">
                "URGENTE: Sua conta será BLOQUEADA agora! Clique no link abaixo e informe sua SENHA para evitar o cancelamento."
            </div>
            <button class="btn-interativo" onclick="analisarMensagem()">Analisar Mensagem</button>
            <p id="feedback-simulador"></p>
        </section>

        <!-- SEÇÃO INTERATIVA: CHECKLIST -->
        <section class="card">
            <h2>🛡️ Meu Escudo Digital</h2>
            <p>Marque o que você já faz para ficar seguro:</p>
            <label><input type="checkbox" class="check-seguranca" onchange="atualizarEscudo()"> Tenho o PIN (senha) no meu WhatsApp.</label><br>
            <label><input type="checkbox" class="check-seguranca" onchange="atualizarEscudo()"> Meu celular tem senha para ligar a tela.</label><br>
            <label><input type="checkbox" class="check-seguranca" onchange="atualizarEscudo()"> Eu nunca clico em links de SMS ou e-mail.</label><br>
            <label><input type="checkbox" class="check-seguranca" onchange="atualizarEscudo()"> Eu ligo para o parente antes de fazer Pix.</label><br>
            <h3 id="status-escudo" style="margin-top: 20px;">Nível de Proteção: 0%</h3>
        </section>

        <!-- NOVO: SEÇÃO DE FONTES OFICIAIS -->
        <section id="fontes">
            <h2>🔗 Fontes Oficiais e Ajuda</h2>
            <div class="card">
                <p>Para mais informações seguras, acesse os sites oficiais:</p>
                <a href="https://meubolsofeliz.com.br/" target="_blank" class="link-fonte">➔ Febraban: Meu Bolso Feliz</a>
                <a href="https://www.bcb.gov.br/meubc/faqs/s/pix-seguranca" target="_blank" class="link-fonte">➔ Banco Central: Segurança no Pix</a>
                <a href="https://www.gov.br/governodigital/pt-br/seguranca-e-protecao-de-dados" target="_blank" class="link-fonte">➔ Portal Gov.br: Segurança Digital</a>
            </div>
        </section>
    </main>

    <footer style="text-align: center; margin-top: 4rem; padding: 2rem; border-top: 2px solid #333; color: #888;">
        <p>💡 Compartilhe este guia com seus amigos e proteja quem você ama!</p>
    </footer>

    <script>
        function responderQuiz(escolha) {
            const f = document.getElementById('feedback-quiz');
            if (escolha) {
                f.innerText = "❌ CUIDADO! Isso é um golpe. Bancos nunca pedem para você transferir dinheiro para 'contas seguras'.";
                f.style.color = "#ff4444";
            } else {
                f.innerText = "✅ EXCELENTE! Você identificou o golpe. Bancos nunca fazem esse tipo de pedido.";
                f.style.color = "#ffdd44";
            }
        }

        function analisarMensagem() {
            const c = document.getElementById('caixa-simulador');
            const textoOriginal = "URGENTE: Sua conta será BLOQUEADA agora! Clique no link abaixo e informe sua SENHA para evitar o cancelamento.";
            const novoTexto = textoOriginal.replace(/URGENTE|BLOQUEADA|SENHA|Clique/g, '<span class="perigo-destaque">$&</span>');
            c.innerHTML = novoTexto;
            document.getElementById('feedback-simulador').innerHTML = "⚠️ <strong>Atenção:</strong> Palavras que causam medo ou pedem sua senha são sinais claros de golpe!";
        }

        function atualizarEscudo() {
            const checks = document.querySelectorAll('.check-seguranca');
            let marcados = 0;
            checks.forEach(c => { if(c.checked) marcados++; });
            const total = marcados * 25;
            const status = document.getElementById('status-escudo');
            status.innerText = "Nível de Proteção: " + total + "%";
            if (total === 100) {
                status.style.color = "#ffdd44";
                status.innerText += " - VOCÊ ESTÁ SEGURO! 🎉";
            } else {
                status.style.color = "#ffffff";
            }
        }
    </script>
</body>
</html>
