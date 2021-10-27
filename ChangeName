function onEdit() {
  var HojaActual = SpreadsheetApp.getActiveSheet();
  var HojaActual_Nombre = HojaActual.getName();

  // Sustituir los valores de getRange por el número de fila y columna de donde se tomará el nombre de la hoja
  var HojaActual_NuevoNombre = HojaActual.getRange(1,1).getValue();
  if (HojaActual_NuevoNombre.toString().length>0 && HojaActual_NuevoNombre !== HojaActual_Nombre) {
    HojaActual.setName(HojaActual_NuevoNombre);
  }
}
