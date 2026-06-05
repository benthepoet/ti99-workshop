ASM = xga99.py

bin: src/keyboard.gpl
	$(ASM) src/keyboard.gpl -o out/KEYBOARDG.bin -L out/keyboard.lst

cart: src/keyboard.gpl
	$(ASM) -c src/keyboard.gpl -o out/KEYBOARD.rpk -L out/keyboard.lst