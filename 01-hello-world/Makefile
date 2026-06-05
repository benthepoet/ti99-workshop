ASM = xga99.py

bin: src/hello.gpl
	$(ASM) src/hello.gpl -o out/HELLOG.bin -L out/hello.lst

cart: src/hello.gpl
	$(ASM) -c src/hello.gpl -o out/HELLO.rpk -L out/hello.lst