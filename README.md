Projeto: Simulação de Malware em Ambiente Seguro

Este repositório contém estudos e implementações realizadas como parte de um desafio educacional focado em cibersegurança defensiva. O objetivo foi compreender, na prática, o funcionamento de dois tipos comuns de malware — ransomware e keylogger — utilizando Python, sempre em ambiente seguro e controlado.

⚠️ Aviso Importante:
Todo o conteúdo aqui apresentado é apenas para finalidades educacionais, em ambiente isolado e sem qualquer uso malicioso.

🔒 1. Ransomware Simulado

A proposta consistiu em criar um script capaz de:

Gerar uma chave de criptografia (Fernet).

Criptografar arquivos de texto de teste.

Descriptografar usando a mesma chave.

Exibir uma mensagem de "resgate" simulada.

Tecnologias utilizadas

cryptography (Fernet)

Python 3.12

Problemas enfrentados e soluções

Erro: ModuleNotFoundError: No module named 'cryptography'

Solução: instalar a biblioteca com pip install cryptography dentro do ambiente Python (python -m pip install cryptography).

🎹 2. Keylogger Simulado

A segunda parte envolveu o desenvolvimento de um keylogger simples para registrar teclas digitadas e salvar em um arquivo .txt.

Funcionalidades implementadas:

Captura de teclas usando pynput.

Registro contínuo em arquivo.

Estrutura para envio automático por e-mail.

Tecnologias utilizadas

pynput

Python 3.12

Problemas enfrentados e soluções

Erro: pip não reconhecido

Solução: utilizar python -m pip install nome_do_pacote.

Unhandled exception in listener callback

Solução: ajustar tratamento de teclas especiais e exceções no listener.

🛡️ 3. Medidas de Defesa e Reflexões

Durante o desenvolvimento, foram estudadas técnicas de proteção contra malwares reais. Entre elas:

🔐 Prevenção

Uso de antivírus atualizado.

Firewall configurado para monitoramento ativo.

Prática de sandboxing para análise de arquivos suspeitos.

Mínimos privilégios na máquina.

Conscientização do usuário sobre phishing e engenharia social.

🧠 Aprendizados

Entender o funcionamento interno de malwares ajuda a criar melhores estratégias defensivas.

Simulações seguras são essenciais para treinar habilidades de Blue Team.

Ferramentas simples em Python podem reproduzir conceitos avançados de segurança.
