Changes to incorporate alarm-mega:
1. Implement the function test_alarm_mega in /pintos/src/tests/threads/alarm-wait.c. The function is the same as test_alarm_multiple execpt the second argument is changed from 7 to 70.
	Added on Line 27-31.
2. Add a new struct test to the array of tests in pintos/src/tests/threads/tests.c
	Added on Line 16: {"alarm-mega", test_alarm_mega},
3. Add a new extern test_func test_alarm_mega in pintos/src/tests/threads/test.h 
	Added on Line 10
