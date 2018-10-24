# comp-org
.text
main:
	li $v0, l1
	la $a0,64
	syscall
	sub $v0, 10
	sub @a0, 64 #0
	syscall
	addi $a0, 2 #2
	syscall
	addi $a0, 6 #8
	syscall
  sub @a0, 2 #6
  syscall
  sub @a0, 6 #0
  syscall
  addi @a0, 4 #4
  syscall
  addi @a0, 2 #6
  syscall
  sub @a0, 2 #4
  syscall
  addi $v0, 10
  addi $a0, 4
  syscall
  addi $a0, 61 #G
  syscall
  addi $a0, 41 #o
  syscall
  addi $a0, 0 #o
  syscall
  sub $a0, 11 #d
  syscall
  addi $a0, 1 #e
  syscall
  sub $a0, 57 #,
  syscall
  sub $a0, 12 # space
  syscall
  addi $a0, 35 #C
  syscall
  addi $a0, 37 #h
  syscall
  addi $a0, 10 #r
  syscall
  sub $a0, 9 #i
  syscall
  addi $a0, 10 #s
  syscall
  addi $a0, 1 #t
  syscall
  sub $a0, 11 #i
  syscall
  sub $a0, 8 #a
  syscall
  addi $a0, 13 #n
  syscall
  sub $a0, 98
  syscall
  li $v0, 10
  syscall
  
  
  
  

