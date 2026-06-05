ASM = xga99.py

bin: src/sprites.gpl
	$(ASM) src/sprites.gpl -o out/SPRITESG.bin -L out/sprites.lst

cart: src/sprites.gpl
	$(ASM) -c src/sprites.gpl -o out/SPRITES.rpk -L out/sprites.lst