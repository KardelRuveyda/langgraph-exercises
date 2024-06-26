# LangGraph 🦜🕸️

LangGraph, doğal dil işleme (NLP) ve konuşma tanıma gibi alanlarda kullanılan yapay zeka uygulamaları geliştirmek için kullanılan bir Python kütüphanesidir. Bu kütüphane, dil modellemesi ve akışları (flows) oluşturma konusunda kolaylık sağlar.

## Özellikler

- Dil modellemesi için geniş bir sözlük ve grammer seti.
- Akışlar oluşturmak için basit ve esnek arayüz.
- Yapay zeka projeleri geliştirmek için kullanışlı örnekler ve rehberler.

## Başlangıç

LangGraph'ı kullanmaya başlamak için [kurulum adımları](#kurulum) bölümüne göz atabilirsiniz.

## Kurulum

LangGraph'ı kullanmak için öncelikle Python yüklü olmalıdır. Daha sonra aşağıdaki adımları izleyebilirsiniz:

1. LangGraph'ı pip aracılığıyla yükleyin:**pip install langgraph**
2. LangGraph'ı projenize ekleyin:

```python
from langgraph import LangGraph
from langgraph import LangGraph

graph = LangGraph()
graph.add_node("node1", "Merhaba dünya!")
graph.add_node("node2", "Nasılsınız?")
graph.add_edge("node1", "node2")
graph.set_entry_point("node1")
graph.set_finish_point("node2")

app = graph.compile()


response = app.invoke()
print(response)
```

## Makale

LangGraph hakkında daha fazla bilgi edinmek ve detaylı bir inceleme okumak için aşağıdaki makaleyi ziyaret edebilirsiniz:

<a href="https://ruveydakardelcetin.medium.com/thor-ve-loki-gibi-langchain-ve-langgraphın-güçlü-i̇şbirliği-041b16fe14ba" target="_blank">Thor ve Loki Gibi: LangChain ve LangGraph'ın Güçlü İşbirliği</a>


<img src="https://github.com/KardelRuveyda/langgraph-exercises/assets/33912144/c817bc97-dbca-4656-84ef-98443243270b" alt="image" width="300"/>

