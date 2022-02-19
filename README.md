# CasePetLoveDataAnalyst

O Jupyter Notebook tem como objetivo expor os códigos e cálculos que foram utilizados para preparar a apresentação. Ele contém alguns comentários breves dentro do próprio código que auxiliam na compreensão do que está sendo feito, além de uma separação por tópicos e conclusões mais extensas (escritas em markdown) do que as presentes na apresentação.

Nomenclaturas importantes utilizadas ao longo do notebook:  
> dados_pet = nome dado ao df original;    
dados_petCopy = cópia do df original (contém apenas dados referentes a assinaturas CANCELADAS);  
dados_petPaused = cópia do df original (contém apenas dados referentes a assinaturas PAUSADAS);  
dados_pet['created_year'] = nova coluna no df original, foi utilizada para separar o ano da coluna [created_at];  
dados_pet['deleted_year'] = nova coluna no df original, foi utilizada para separar o ano da coluna [deleted_at];   
dados_petCopy['periodo'] = nova coluna no df CÓPIA, para calcular o período de assinatura dos clientes que cancelaram assinatura;  

Todos os gráficos presentes no Notebook possuem títulos que explicitam os eixos.
