# Corne Split Keyboard (ZMK)

Este directorio contiene los archivos de configuración para el teclado Corne en modo split usando ZMK y nice!nano.

## Archivos
- `corne.conf`: Configuración general del teclado (split, BLE, debounce, etc).
- `corne.keymap`: Mapeo de teclas (layers base y raise, 4x6 por lado).
- `corne.overlay`: Device tree overlay para la matriz y pines de ambos lados.
- `Kconfig.shield` y `Kconfig.defconfig`: Configuración de shield para ZMK.

## Compilación
Compila usando el shield `corne` para ambos lados. Si usas Bluetooth, el mismo firmware sirve para ambos. Si usas split por cable, avisa para ajustar la configuración. 