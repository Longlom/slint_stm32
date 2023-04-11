# Repo for using slint+rust on STM32H735 with display

To flash code need to install cargo flash and then use 

`cargo flash --no-default-features  --features=mcu-board-support/stm32h735g --target=thumbv7em-none-eabihf --release --chip STM32H735IGK6`