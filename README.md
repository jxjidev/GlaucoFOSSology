Relatório de Auditoria de Licenciamento de Software
Projeto Python: Inteligência Artificial e Previsões
1. Introdução
Este relatório visa analisar a conformidade de licenciamento das bibliotecas utilizadas no projeto "Inteligência Artificial e Previsões" desenvolvido em Python. A auditoria é realizada com foco em garantir que o projeto esteja em conformidade com as licenças das bibliotecas open source, evitando problemas legais ou restrições indevidas.

2. Ferramenta Utilizada: Análise Manual Baseada em FOSSology
A ferramenta FOSSology, amplamente utilizada para auditoria de licenciamento de software, é conhecida por realizar uma varredura completa nas licenças de projetos open source. Nesta análise, seguimos uma abordagem manual, identificando as bibliotecas utilizadas nos notebooks fornecidos e mapeando suas licenças.

3. Bibliotecas Identificadas e Suas Licenças
Durante a análise dos notebooks enviados ("gabarito 1.ipynb" e "inicial 1.ipynb"), foram identificadas as seguintes bibliotecas:

![image](https://github.com/user-attachments/assets/adf2844b-7ece-490f-974f-905399200d41)

Biblioteca	Versão	Licença	Observações
NumPy	1.21.0	BSD	Licença permissiva, sem restrições significativas.
Pandas	1.3.0	BSD	Licença permissiva, adequada para projetos open source.
Scikit-learn	0.24.2	BSD	Sem restrições de uso, amplamente utilizada.
Matplotlib	3.4.2	PSF	Licença permissiva, foco em visualizações.
TensorFlow	2.5.0	Apache 2.0	Licença permissiva, inclui cláusulas de patente.
4. Análise de Conformidade
Após a revisão das licenças acima:

Licenças Permissivas: Todas as bibliotecas analisadas estão sob licenças permissivas (BSD, PSF, Apache 2.0), permitindo o uso, modificação e redistribuição sem restrições severas. Essas licenças são ideais para o desenvolvimento de projetos open source e comerciais.

Cláusulas de Patente (Apache 2.0): A biblioteca TensorFlow, licenciada sob a Apache 2.0, possui cláusulas que envolvem patentes, o que pode ser relevante em projetos comerciais que pretendem redistribuir o código.

5. Possíveis Problemas de Conformidade
Nenhum problema significativo de conformidade foi identificado. Todas as bibliotecas utilizadas estão sob licenças compatíveis com o desenvolvimento e distribuição de projetos tanto open source quanto comerciais.

6. Recomendações
Manter a Documentação Atualizada: É importante manter um arquivo LICENSE ou NOTICE no projeto listando as licenças das bibliotecas utilizadas.
Verificação Regular: Em caso de atualizações de bibliotecas ou inclusão de novos pacotes, recomenda-se realizar auditorias regulares para garantir a conformidade contínua.
7. Conclusão
A auditoria realizada confirmou que o projeto "Inteligência Artificial e Previsões" está em conformidade com as licenças das bibliotecas utilizadas. Nenhum risco significativo foi identificado, permitindo o desenvolvimento contínuo sem preocupações com violações de licenciamento.

