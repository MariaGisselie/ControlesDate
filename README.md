# Proyecto Interfaz Controles DatePicker y ColorPicker
Se desarrolló una interfaz gráfica de usuario (GUI) en JavaFX que permite a los usuarios seleccionar una fecha y un color, y visualizar estas selecciones en la interfaz.
# Selector de fechas
Un control de selección de fecha que permite a los usuarios seleccionar una fecha específica desde un calendario desplegable
![image](https://github.com/MariaGisselie/ControlesDate/assets/169214799/90b8cf11-8229-4403-9dbc-9804a76c80ce)
# Selector de color
![image](https://github.com/MariaGisselie/ControlesDate/assets/169214799/17145ce6-e82d-489c-80dc-b890b16f2e07)
# Diseño de VBox
Utilice un diseño vertical (VBox) para organizar los controles de manera ordenada y clara.
    VBox contenedor = new VBox();
       contenedor.setSpacing(10);
       contenedor.getChildren().addAll(titulo,fechaLabel, fechaPicker, colorLabel, colorPicker, confirmarButton);
# Botón
  Button confirmarButton = new Button("Confirmar");


