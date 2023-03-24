# report-01
1. $ wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
2. $ tar -xvf boost_1_69_0.tar.gz
3. $ ls -l | grep "^-" | wc -l
4. $ ls -l -R | wc -l
5. $ ls -l -R | grep -c *.hpp  
   $ ls -l -R | grep -c *.cpp 
   $ ls -l -R | grep -v *.hpp | grep -v *.cpp | grep -v | wc -l   
6. $ find $PWD -type f -name any.hpp
7. $ grep -R -l "boost::asio"
8. $ ./bootstrap.sh --prefix=boost_output
   $ ./b2 install    
9. $ mv ~/boost_1_69_0/boost_output/lib ~/boost-libs
10. $ du -h -a 
11. $ du -h -a | sort -r -h | head -n 10
