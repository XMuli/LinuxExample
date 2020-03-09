#第一个版本-----------------
#mainApp: *.cpp
#	g++-9 *.cpp -o mainApp



#第二个版本-----------------
#mainAPP: *.o
#	g++-9 *.o -o mainApp

#*.o: *.cpp
#	g++-9 -c *.cpp


#第三个版本-----------------
#val_a = ExAdd.o ExDiv.o ExMul.o ExSub.o main.o  #赋值给变量 val_a
#val_app = mainAPP

#$(val_app): $(val_a)
#	g++-9 $(val_a) -o $(val_app)    #g++-9 $^ -o $(val_app)


#%.o: %.cpp   # 模式匹配，相当于公式，两个百分号是同一个 "量"
#	g++-9 -c $< -o $@


#第四个版本-----------------
val_a = $(wildcard ./*.cpp)
val_b = $(patsubst %.cpp, %.o, $(val_a))
val_app = mainAPP

$(val_app): $(val_b)
	g++-9 $^ -o $(val_app)


%.o: %.cpp
	g++-9 -c $< -o $@


# 附加文件清理-----------------
# clean:
#	rm *.o $(val_app)  #这种写法是错误而，仅能够找到当前规则下的文件，而 clean 只是(中建)目标，而非第一行的终极目标 


#(若是最存在同名文件) ，其目标文件 claen 又没有依赖文件，所以总是最新的，也就不会执行 make clean 的下面命令
#.PHONY: clean   #明伪目标: 不会做依赖和更新检查( 文件日期时间先后判断)
clean: 
#	-mkdir /abc  # 第一个"-"   表示若是执行失败，则执行后面会的命令，
	-rm $(val_b) $(val_app)   #后面-f 是强制执行   
