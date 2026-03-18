SIMULADOR DE CRÉDITO, VERSIÓN INICIAL

1. Instala Python 3.11 o superior.
2. Abre una terminal en la carpeta donde guardaste los archivos.
3. Instala dependencias:
   pip install -r requirements_simulador_credito.txt
4. Ejecuta la app:
   streamlit run app_simulador_credito.py
5. Streamlit te mostrará una URL local, normalmente:
   http://localhost:8501
6. Para abrirla desde tu celular en la misma red WiFi, usa:
   streamlit run app_simulador_credito.py --server.address 0.0.0.0
   Luego abre en tu celular:
   http://IP_DE_TU_PC:8501

NOTAS
- Esta primera versión está hecha para el caso específico conversado.
- Ya permite incluir o excluir ITE y gastos notariales del monto financiado.
- La siguiente mejora lógica sería permitir más tipos de estructura de cuotas.
