🔬 SM2 - Laboratório de Classificação Visual

Disciplina: Engenharia de Prompt e Aplicações em IA (2026.1)

📝 Visão Geral

Este projeto explora os fundamentos de Visão Computacional através da criação de um modelo de classificação de imagens. O objetivo principal foi entender o ciclo de vida de um modelo de Machine Learning: coleta de dados, treinamento supervisionado e inferência em tempo real.

O classificador foi treinado para distinguir entre duas categorias específicas (Calvo vs. Careca), permitindo observar como o modelo identifica padrões sutis de textura e formas capilares.

🚀 Especificações Técnicas

Engine: Teachable Machine (Google)

Pipeline: Classificação de Imagens (Standard Image Model)

Dataset: 40 amostras totais (20 imagens por classe)

Validação: Testes realizados via upload de arquivos e stream de câmera ao vivo.

🖼️ Demonstração e Resultados

O modelo atingiu 100% de confiança nos testes controlados, demonstrando uma separação clara entre as classes após o processamento das épocas de treinamento.

Nota: Durante os testes, foi possível observar a importância da iluminação e do ângulo da imagem para manter a precisão da inferência.

📊 Principais Aprendizados

Feature Extraction: Compreensão de como a IA extrai características visuais para diferenciar classes similares.

Data Quality: Identificação de que a qualidade e a diversidade das amostras (backgrounds diferentes, ângulos variados) são mais cruciais que a quantidade bruta de dados.

Inferência: Análise de performance do modelo em ambientes não controlados (câmera em tempo real).

🔧 Fluxo de Desenvolvimento

Coleta: Definição das classes e captura de 20 amostras de alta fidelidade para cada.

Treinamento: Processamento via nuvem para geração dos pesos do modelo.

Avaliação: Teste de estresse com imagens fora do dataset original para verificar a capacidade de generalização.
