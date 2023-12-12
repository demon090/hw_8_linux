## Вывести на экран 3 раза имя пользователя, от которого запускается команда.

useriam@useriam-VirtualBox:~$ chmod u+x user.sh

useriam@useriam-VirtualBox:~$ cat user.sh

#!/bin/bash

for i in 1 2 3; do echo $USER; done

useriam@useriam-VirtualBox:~$ ./user.sh

useriam

useriam

useriam

useriam@useriam-VirtualBox:~$ 

## Вывести с помощью цикла while все четные числа от 0 до 100 включительно.

useriam@useriam-VirtualBox:~$ nano count.sh

useriam@useriam-VirtualBox:~$ chmod u+x count.sh

useriam@useriam-VirtualBox:~$ cat count.sh

#1/bin/bash



counter=0

while [ $counter -lt 101 ]

do

  echo $counter

  counter=$((counter+1))

done

useriam@useriam-VirtualBox:~$ ./count.sh

0

1

2

3

4

5

6

7

8

9

10

11

12

13

14

15

16

17

18

19

20

21

22

23

24

25

26

27

28

29

30

31

32

33

34

35

36

37

38

39

40

41

42

43

44

45

46

47

48

49

50

51

52

53

54

55

56

57

58

59

60

61

62

63

64

65

66

67

68

69

70

71

72

73

74

75

76

77

78

79

80

81

82

83

84

85

86

87

88

89

90

91

92

93

94

95

96

97

98

99

100



