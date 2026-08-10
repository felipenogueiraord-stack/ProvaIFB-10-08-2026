tamanhoArquivo = float(input('Digite o tamanho do arquivo para download em Mb: '))
velocidade = float(input('Digite a velocidade do seu link de internet e Mbps: '))

def tempoFinal():
    total = tamanhoArquivo * 8 / velocidade
    total / 60


tempoFinal()
    
