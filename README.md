# Treinamento Automático de Classificador Haar/LBP (OpenCV)

**Versão otimizada – 2025‑05**

Este projeto fornece uma pipeline automatizada para treinamento de classificadores Haar ou LBP utilizando os utilitários `opencv_createsamples` e `opencv_traincascade`. Ideal para quem deseja criar detectores personalizados de objetos com o OpenCV (por exemplo, mouse de computador, logotipos, placas, etc.).

---

##  Funcionalidades

- Anotação interativa de imagens positivas.
- Geração automática da lista de imagens negativas (`bg.txt`).
- Criação do arquivo `.vec` com aumento de dados.
- Treinamento completo com parâmetros configuráveis.
- Saída final no formato `cascade.xml` pronto para uso.

---

## 💡 O que é isso?

Este projeto é um **pipeline completo para treinar detectores de objetos usando OpenCV (Haar ou LBP)**. Basta ter imagens positivas e negativas — o script cuida do resto: anotação, preparação, aumento de dados, criação de `.vec` e treinamento.

Ideal para detectar objetos simples em imagens, como mãos, ferramentas, eletrônicos, etc.

---
