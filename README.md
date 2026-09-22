# Classe EIC-BCC-TCC

Define um modelo LaTeX para TCCs do BCC Cefet/RJ. O projeto possui os seguintes arquivos:
- **figuras/figure.png**: Exemplo de figura a ser utilizada no texto;
- **ficha.pdf**: Exemplo de arquivo de ficha catalográfica contendo as informações necessárias sobre solicitação de ficha para a biblioteca;
- **eic-bcc-tcc.cls**: Classe para escrita do TCC em LaTeX;
- **apalike-pt.bst**: Estilo bibliográfico em português, usado por padrão no template;
- **apalike.bst**: Estilo bibliográfico em inglês, para uso alternativo quando necessário;
- **references.bib**: Exemplo de arquivo contendo as informações bibliográficas das referências;
- **main.tex**: Exemplo de uso da classe ```eic-bcc-tcc```.
- **Trabalho de Conclusao EIC BCC.pdf**: PDF gerado usando a classe ```eic-bcc-tcc``` contendo a explicação sobre os elementos de um TCC.

Por padrão, o template utiliza o estilo bibliográfico em português:

```latex
\bibliographystyle{apalike-pt}
```

Caso seja necessário usar o estilo em inglês, basta alterar para:

```latex
\bibliographystyle{apalike}
```

Essa configuração fica na definição do comando `\referencepage`, no arquivo `eic-bcc-tcc.cls`.

## Síntese do material: IA generativa no ensino superior

O estudo de Jin et al. (2025), publicado em *Computers and Education: Artificial Intelligence*, analisa políticas e diretrizes institucionais relacionadas à adoção de inteligência artificial generativa no ensino superior, considerando 40 universidades de seis regiões globais. Os resultados mostram que as instituições buscam conciliar o uso da IA com a integridade acadêmica, a melhoria do ensino e da aprendizagem, o desenvolvimento da alfabetização em IA e a equidade de acesso. O estudo também destaca desafios éticos relacionados à privacidade e à segurança de dados, à transparência sobre o uso de ferramentas de IA, à avaliação crítica dos conteúdos gerados e ao risco de uso inadequado em atividades acadêmicas. Entre as medidas identificadas estão a criação de diretrizes para o uso responsável da IA, adaptações em métodos de avaliação, capacitação de professores e estudantes, canais de comunicação entre os diferentes grupos da comunidade acadêmica e definição de responsabilidades para docentes, estudantes e administradores. Os autores ressaltam, entretanto, que ainda existem lacunas na formulação de políticas abrangentes e na avaliação contínua dos impactos da IA, indicando a necessidade de uma abordagem institucional colaborativa, transparente e adaptável.

**Referência:** JIN, Yueqiao et al. *Generative AI in higher education: A global perspective of institutional adoption policies and guidelines*. Computers and Education: Artificial Intelligence, v. 8, 2025, 100348. DOI: 10.1016/j.caeai.2024.100348.
