# Treinamento Automático de Classificador Haar/LBP (OpenCV)

**Versão otimizada – 2025‑05**

Este projeto fornece uma pipeline automatizada para treinamento de classificadores Haar ou LBP utilizando os utilitários `opencv_createsamples` e `opencv_traincascade`. Ideal para quem deseja criar detectores personalizados de objetos com o OpenCV.

---

##  Funcionalidades

- Anotação interativa de imagens positivas.
- Geração automática da lista de imagens negativas (`bg.txt`).
- Criação do arquivo `.vec` com aumento de dados.
- Treinamento completo com parâmetros configuráveis.
- Saída final no formato `cascade.xml` pronto para uso.
