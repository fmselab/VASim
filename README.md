## modifications

in file 

libs\MNRL\C++\src\mnrl_schema.asm  bits 32

in file

libs\MNRL\C++\Makefile

ifeq ($(OS),Windows_NT)
# ANGELO GARGANTINI FOR 32 bits 
#	NASMFLAGS = -fwin64
	NASMFLAGS = -fwin32
endif
