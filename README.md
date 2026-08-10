tamanhoArquivo = float(input('Digite o tamanho do arquivo para download em Mb: '))
velocidade = float(input('Digite a velocidade do seu link de internet e Mbps: '))

def tempoFinal(tamanho, vel):
  
    total_segundos = tamanho * 8 / vel
    total_minutos = total_segundos / 60
    return total_minutos

tempo_download_minutos = tempoFinal(tamanhoArquivo, velocidade)
print(f"O tempo aproximado de download é de {tempo_download_minutos:.2f} minutos.")
