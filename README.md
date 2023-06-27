# Aplicação para Detecção da MPOX utilizando MobileNet

#### Iedntificação do dataset:

* O número **0** será utilizado para categorizar "MPOX-Negativo".
  * Total de imagens: 1890

* O número **1** será utilizado para categorizar "MPOX-Positivo".
  * Total de imagens: 1531
 
_Total geral de imagens:  3421_   


* Proporção de treino, teste e validação: _70:15:15_



#### Organização do diretório do dataset:

* dataset/
  - train/
    - 0/
    - 1/      
  - test/
    - 0/
    - 1/ 
  - valid
    - 0/
    - 1/


A pasta _dataset_ possui a separação realizada na execução do artigo. Para gerar uma nova execução, basta deletar as pastas internas e mover as pastas _0_ e _1_ da pasta _backup_.

Todas imagens possuem um prefixo que as identificam como MPOX-positivo quando inicial com "M" e MPOX-negativo quando incial com "NM".
