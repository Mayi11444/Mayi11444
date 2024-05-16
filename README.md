# Diagrama de Flujo del Certificado de Historia de Dominio

```mermaid
graph TD
    A[1. INFORMACIÓN DEL PREDIO]
    B[2. INFORMACIÓN DEL CATASTRO MUNICIPAL]
    C[3. MOVIMIENTOS DEL PREDIO EN ORDEN CRONOLÓGICO]

    subgraph Información del Predio
        A1[Ubicación: Ciudadela Kennedy, Calles Segunda y D, parroquia Tarqui]
        A2[Dimensiones: NORTE 15.35m, SUR 15.52m, ESTE 24.00m, OESTE 25.50m]
        A3[Área: 376.38m², Titulares: Blanca Rosa Rodríguez, Héctor Colón Rodríguez (Her.), Patricia Carolina Rodríguez]
        A4[Estado: Activo, Pavimentación: SI, Acera: SI, Bordillo: SI, Alumbrado: SI, Red Telefónica: SI, Alcantarillado: SI, Agua Potable: SI]
    end

    subgraph Información del Catastro
        B1[Solicitante: Héctor Colón Rodríguez, Fecha de Emisión: 11-03-2024, Fecha de Vencimiento: 09-06-2024]
    end

    subgraph Movimientos del Predio
        C1[2020/NOV/27 Posesión Efectiva, Notaría Trigésima Séptima, Guayaquil, Causante: Blanca Rosa Rodríguez]
        C2[2020/MAR/03 Posesión Efectiva, Notaría Cuarta, Samborondón, Causante: María Neli Rodríguez, Herederos: Isidoro Alejandro Vallejo]
        C3[2020/MAR/03 Adquisición de Dominio, Notaría Cuarta, Samborondón, Propietario: Isidoro Alejandro Vallejo]
        C4[2020/MAR/03 Cesión de Derechos y Acciones Hereditarios, Notaría Cuarta, Samborondón, Cedente: Isidoro Alejandro Vallejo, Cesionario: Patricia Carolina Rodríguez]
        C5[2019/DIC/27 Cancelación de Hipoteca, Notaría Décimo Cuarta, Guayaquil, Acreedor: Banco Territorial S.A.]
        C6[1978/MAY/30 Compraventa, Notaría Quinta, Guayaquil, Compradores: Blanca Rosa Rodríguez, Nelly Rodríguez, Vendedores: Gladys Chichonis, Marina Delgado, Enrique Rodríguez, Galo Rodríguez]
    end

    A --> A1
    A --> A2
    A --> A3
    A --> A4

    B --> B1

    C --> C1
    C --> C2
    C --> C3
    C --> C4
    C --> C5
    C --> C6
