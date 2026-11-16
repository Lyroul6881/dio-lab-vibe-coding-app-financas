# 💸 App de Organização de Finanças Pessoais, "Meu bolso"


```
#Contexto

Quero criar um aplicativo de organização de finanças pessoais que seja visual, intuitivo e interativo, com a conversa como forma rápida de lançar gastos. A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários longos nem planilhas complexas.

O painel visual (gráficos de pizza, porcentagens e saldo) é a tela principal. O chat é o atalho para registrar um gasto em segundos. O app é pensado primeiro para o celular e, em telas grandes, passa a usar menu lateral e duas colunas.

#Problema

Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e oferecem pouca personalização. Quero resolver isso com uma experiência rápida de lançamento, um painel que mostra para onde o dinheiro está indo e recomendações automáticas de economia.

#Público-alvo

Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

Persona de referência: jovem de 18 a 30 anos, com renda pequena ou variável, que já tentou usar planilha ou outro app e desistiu por dar trabalho. Usa o celular o dia todo e não entende (nem quer entender) termos financeiros complicados.

#Princípios do produto

Visual primeiro: o usuário entende a situação do mês em uma olhada, sem ler tabelas.

Rápido: registrar um gasto leva poucos segundos e poucos toques.

Linguagem simples: português claro, sem jargão, com tom educativo e acolhedor.

Sem punição: avisos e dicas ajudam, não culpam.

#Funcionalidades-chave (MVP)

Painel principal: saldo do mês, total de entradas e de saídas, e gráfico de pizza por categoria com porcentagens. Ao tocar em uma fatia, o usuário vê os lançamentos daquela categoria. Um aviso mostra contas atrasadas ou perto do vencimento.

Lançamento rápido por frase: o usuário escreve algo como “gastei 35 no mercado” ou “paguei 12 de uber ontem” e o app identifica valor, categoria e data.

Lançamento manual: formulário simples como plano B, para quando a frase não for entendida ou o usuário preferir.

Receitas e despesas: registrar o que entra (salário, extras) e o que sai, para calcular saldo e porcentagem da renda gasta.

Categorias automáticas e editáveis: o app sugere a categoria pelas palavras da frase, e o usuário corrige com um toque.

Metas e orçamento por categoria: definir um limite (por exemplo, lazer: R$ 200/mês) e acompanhar com barra de progresso e aviso ao chegar perto do limite.

Contas a pagar: cadastrar boletos e contas com data de vencimento. O app separa as atrasadas, as dos próximos 7 dias e as mais adiante. Ao tocar em “Paguei”, a conta vira um gasto lançado.

Assistente financeiro: chat para perguntar sobre os próprios números, como “onde posso economizar?” ou “quais contas pago primeiro?”. Ao perguntar, um resumo dos números do mês é enviado ao Claude para gerar a resposta.

Dicas automáticas: sugestões curtas no painel baseadas nos dados, como “você gastou 40% do mês com lazer; que tal reduzir um pouco?”.

Resumo mensal: saldo, média por dia, comparação com o mês anterior e as maiores categorias.
```

Interações com a IA:

>Eu tinha em mente um app visualmente intuitivo, fácil de usar e bem interativo, sabe? com aqueles gráficos em pizza, porcentagens e tal.

>Beleza! Agora vamos por a mão na massa e criar essa pagina!

>Em resposta aos pontos em aberto:  Quero um pouco completo, sem exagero. 

>Tera como uso principal no celular e os dados devem ficar apenas no aparelho do usuario

Resultado final: https://claude.ai/artifact/WKHvxzyaqiRXJAFKfcsyay

<img width="1306" height="854" alt="image" src="https://github.com/user-attachments/assets/b1f139ff-36f0-4d18-b95b-40dfd70f25a2" />

Resumo do APP:

O Meu Bolso é um app de finanças pessoais pensado primeiro para o celular, que também se adapta a telas grandes, como no print que você mandou. Ele mostra para onde o seu dinheiro foi de um jeito visual, sem planilhas.

Lançar gastos: você escreve algo como “gastei 35 no mercado” e ele identifica valor, categoria e data. Também dá para preencher manualmente.
Painel: mostra saldo, entradas e saídas do mês, com um gráfico de pizza por categoria e porcentagens.
Contas a pagar: cadastra boletos e vencimentos, avisa o que está atrasado ou perto de vencer e, ao tocar em “Paguei”, lança o valor nos gastos.
Metas: limites por categoria, com barras de progresso.
Resumo e dicas: comparação com o mês anterior e sugestões curtas de economia.
Assistente (✨): um chat para perguntar sobre os seus números, como “onde posso economizar?”.

Os dados ficam só no aparelho de quem usa. A única exceção é o assistente, que envia um resumo dos números do mês ao Claude para responder.

Reflexão sobre o processo:

# O que funcionou bem
Começar pelo PRD antes de criar o app. A revisão mostrou lacunas (receitas, categorias editáveis, privacidade) e uma contradição entre o texto, centrado em chat, e o que eu queria de verdade, um app visual com gráficos. Com isso, a primeira versão já saiu próxima do que eu imaginava, e foi fácil pedir novos ajustes em etapas, como contas a pagar, assistente e layout para telas grandes.

# O que não funcionou como o esperado
Alguns problemas só apareceram quando eu vi o resultado, como o texto com pouco contraste no card de saldo no modo escuro. O PRD também prometia coisas que o app ainda não fazia, como “aprender com as correções” de categoria, e isso precisou ser corrigido. Além disso, a IA não conseguiu testar o app no celular, então dependi dos meus prints para encontrar os erros.

# O que aprendi sobre conversar com IAs
Quanto mais claro o objetivo, melhor o resultado. Pedir uma revisão antes de construir evita retrabalho, e mandar print mostra o problema melhor do que descrevê-lo. Também aprendi a conferir o que a IA afirma em vez de aceitar de primeira, inclusive sobre privacidade, como no assistente, que envia um resumo dos dados ao Claude.




## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
