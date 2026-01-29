p1-b solução --> tar -xzvf challenges.tar.gz
p2-b solução --> cd challenges
p3 -b solução --> ls
p4-b solução --> mkdir foo
p5-i solução --> mkdir -p foo/bar/1/2/3
p6-b solução --> rm -rf foo
p7-b solução --> echo "hello world"
p8-b solução --> echo "hello world" > hello.txt
p9-b solução --> touch empty.txt
p10-b soluções  --> rm empty.txt
p11-i soluções --> >empty.txt
p12-i soluções --> echo -n >empty.txt
p13-b soluções --> cp hello.txt goodbye.txt
p14-b soluções --> mv goodbye.txt hello_copy.txt
p15-i soluções --> diff hello.txt hello_copy.txt
p16-b soluções --> cat hello.txt hello_copy.txt > 2_hellos.txt
p17-b soluções --> pwd
p18-b soluções --> ls -l 
p19-b soluções --> echo "texto adicionado"|sudo tee -a restricted.txt
p20-b soluções -->( a partir da pasta challanges) ./hello_executable
p21-b soluções --> challenges/challenge_20 ( a partir do repositorio usando chmod +x caminho para liberar permissao)
p22-b soluções --> sudo apt install build-essesntial e depois ggc compile_mec -o compile_me
p23-a soluções --> challenges/redirect >output.txt
p24-b soluções --> date
p25-b soluções --> ps aux
p26-b soluções --> nproc
p27-b soluções --> uname -r
p28-b soluções --> grep -R "You found the needle in the haystack!"challenges/bunch_of_files/
p29-b soluções --> head -n 25 challenges/people.csv
p30-b soluções --> tail -n 25 challenges/people.csv
p31-i soluções --> diff challenges/gretting1.txt greeting2.txt
p32-i soluções --> echo "hello";sleep 5 ; echo "world"
p33-i soluções --> dd if=/dev/zero of=ono_mb.txt bs=1M count=1
p34-i soluções --> dd if=/dev/urandom of=two_mb.txt bs=1M count=2
p35-i soluções -->wc -l README.txt
p36-b soluções --> tac README.txt
p37-i soluções --> cut -d "," -f2 challenges/people.csv
p38-a soluções ->cut -d ","f2 challenges/people.csv|sort|uniq|wc -l
p39-a soluçoes --> sim cut id "," -f challenges/people.csv|head (comprova)
p40-a soluções --> sed 1d challenges/people.csv|cut -d',' -f2 | sort |uniq| wc -l
