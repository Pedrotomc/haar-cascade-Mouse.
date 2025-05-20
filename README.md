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


# 📦 Pipeline Automatizado para Treinamento de Classificadores Haar/LBP com OpenCV

Este repositório fornece um **pipeline completo e automatizado** para o treinamento de classificadores em cascata usando as bibliotecas do OpenCV. O processo cobre desde a anotação das amostras positivas até a geração do modelo final `cascade.xml`.

> ✅ Suporte a classificadores `HAAR` e `LBP`  
> 🧠 Foco em simplicidade, reprodutibilidade e aumento de dados  
> 🖼️ Interface de anotação manual com `cv2.selectROI`  

---

## 🧭 Objetivo

Facilitar o processo de treinamento de classificadores personalizados para detecção de objetos com OpenCV, sem exigir conhecimentos avançados de linha de comando ou scripts fragmentados. Ideal para pesquisadores, estudantes ou profissionais que desejam treinar detectores para objetos específicos como:

- Ferramentas manuais
- Equipamentos eletrônicos
- Mãos ou gestos
- Produtos em linhas de montagem
- Etc.

---

## 🧰 Funcionalidades

- ✅ Anotação assistida (interface GUI via OpenCV)
- ✅ Geração automática de arquivos `.txt` para positivos e negativos
- ✅ Criação de arquivos `.vec` com aumento de dados
- ✅ Treinamento completo via `opencv_traincascade`
- ✅ Controle de parâmetros por linha de comando

---

## 🏗️ Requisitos

| Recurso                     | Detalhes                                 |
|----------------------------|------------------------------------------|
| Python                     | 3.7+                                     |
| OpenCV                     | `opencv-python` e OpenCV com binários C++|
| SO recomendado             | Windows (ajustável para Linux/macOS)     |
| Executáveis necessários    | `opencv_createsamples.exe`, `opencv_traincascade.exe` |

---

## 📁 Estrutura de diretórios

```bash
.
├── auto_pipeline.py            # script principal
├── imagens/
│   ├── positivas/              # imagens com o objeto desejado
│   └── negativas/              # imagens sem o objeto
├── annotations/                # arquivos gerados automaticamente (.txt, .vec)
└── training/                   # diretório de saída com cascade.xml
