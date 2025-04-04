# Projeto de Reconhecimento de Texto com IA do Azure 🚀

Este projeto demonstra o uso dos **serviços cognitivos de Visão Computacional** e **IA generativa do Azure** para **extrair texto de imagens** (OCR - Optical Character Recognition). Ideal para automatizar tarefas como leitura de documentos, notas fiscais, placas, etc.

## 🧠 Tecnologias Utilizadas

- Azure AI Vision (OCR)
- Azure OpenAI (análise de conteúdo extraído)
- Git e GitHub
- Imagens e documentos com texto real

---

## 🖼 Inputs

As imagens utilizadas estão na pasta `/inputs`. Exemplos:

- `nota_fiscal.jpg`: imagem de uma nota fiscal real.
- `quadro_branco.png`: captura de anotações feitas à mão.

---

## 📄 Outputs

Os resultados extraídos pela IA estão na pasta `/output` em formatos `.txt` e `.json`.

Exemplo de resultado:
```json
{
  "document": "Total: R$ 75,90\nData: 02/04/2025\nProduto: Arroz - 1kg\n..."
}
