# Distancia-entre-dois-pontos-
 
import math
>>> def main():
	
	
	xA = int(input('coloque o valor da abcissa:'))
	xB = int(input('coloque o valor da abcissa:'))
	yA = int(input('coloque o valor da abcissa:'))
	yB = int(input('coloque o valor da abcissa:'))
	
	
	distAB = math.sqrt((xB-xA)**2 + (yB-yA)**2)
	
	print('a distancia entre os pontos eh:', distAB, 'unidade de medida')
