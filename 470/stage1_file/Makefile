
clean:
	rm -f *.o *.elf *.self *.470 *.bin *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o

all:
	rm -f *.o *.elf *.self *.470 *.bin *.470c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470C --no-print-directory

	rm -f *.o *.elf *.470 *.bin *.470d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470D --no-print-directory

	rm -f *.o *.elf *.470 *.bin *.470c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470C_DEBUG --no-print-directory

	rm -f *.o *.elf *.470 *.bin *.470d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470D_DEBUG --no-print-directory

	rm -f *.o *.elf  *.470 *.bin *.470c *.470d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o

dbg:
	rm -f *.o *.elf *.self *.470 *.bin *.470c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470C_DEBUG --no-print-directory

	rm -f *.o *.elf *.470 *.bin *.470d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470D_DEBUG --no-print-directory

	rm -f *.o *.elf  *.470 *.bin *.470c *.470d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o

re:
	rm -f *.o *.elf *.self *.470 *.bin *.470c *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470C --no-print-directory

	rm -f *.o *.elf *.470 *.bin *.470d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_470D --no-print-directory

	rm -f *.o *.elf  *.470 *.bin *.470c *.470d *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
