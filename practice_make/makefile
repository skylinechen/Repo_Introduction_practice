test_3: test_1
	@cat *.txt

test_1: test_2
	@echo "Create 222.txt" 
	@touch 222.txt	
	@echo 111 > 222.txt
	@echo 333 > 444.txt
test_2:
	@echo "Create 444.txt"
	@touch 444.txt

clean:
	@echo "Cleaninggggggggg"
	@rm -f *.txt

#target: dependencies
#<TAB> command

#First to create test_2 and you can put test_2 on the dependencies on test_1.
#use "@" can ignore to show command in terminal.

#test_2
#	create file
#test_1 
#	create file and echo in file
#test_3
#	show file content
#
#.DEFAULT_GOAL can definit to execute which target but only one target can execute
# all can call many targets to execute
