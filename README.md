# programas-laboratorio--1
def conversor_divisas():
    # Tasa de cambio actualizada (Referencia Banguat 11/05/2026)
    tasa_cambio = 7.62478 
    
    print("--- Conversor de Quetzales (GTQ) a Dólares (USD) ---")
    
    try:
        quetzales = float(input("Ingrese la cantidad en Quetzales: Q"))
        
        # Operación: Quetzales / Tasa de cambio = Dólares
        dolares = quetzales / tasa_cambio
        
        print(f"\nQ{quetzales:,.2f} quetzales equivalen a:")
        print(f"${dolares:,.2f} dólares estadounidenses")
        
    except ValueError:
        print("Error: Por favor, ingrese un valor numérico válido.")

if __name__ == "__main__":
    conversor_divisas()
