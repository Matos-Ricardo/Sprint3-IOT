# Sprint3-IOT

Detector de Emoções com DeepFace
🎯 Objetivo

Este projeto implementa um sistema simples de detecção de emoções em tempo real usando Python, OpenCV e DeepFace.
O modelo reconhece as emoções Feliz, Triste, Medo e Neutro a partir da imagem capturada pela câmera do computador.

▶️ Execução

Instale as dependências:

pip install -r requirements.txt


Execute o programa:

python detector.py


Pressione Q na janela do vídeo para encerrar a execução.

📦 Dependências

Python 3.8 ou superior

OpenCV

DeepFace

TensorFlow ou PyTorch (DeepFace usa um backend)

Arquivo requirements.txt sugerido:

opencv-python
deepface
tensorflow

⚙️ Parâmetros

No código é possível ajustar:

Emoções analisadas → Feliz, Triste, Medo e Neutro.

Cores das caixas → cada emoção tem uma cor definida.

Tecla de saída → Q fecha a janela.

📂 Organização do Código

detector.py → código principal com captura de vídeo e análise de emoções.

requirements.txt → lista de dependências para instalação.

README.md → documentação do projeto.

🧾 Nota Ética sobre Uso de Dados Faciais

O reconhecimento de emoções envolve dados biométricos sensíveis.
Este projeto tem finalidade exclusivamente acadêmica e de aprendizado.
Não deve ser utilizado para fins comerciais, de vigilância ou sem o consentimento explícito dos indivíduos.
Reforçamos a importância de respeitar a privacidade e ética no uso de dados faciais.
