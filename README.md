# Result Profiling with Jmeter
## GET all-student
### GUI
![GUI Result GET all-student](profiling_result/result_gui_all-student.png)
### CLI
#### Pre-Optimization
![CLI Result GET all-student pre](profiling_result/result_cli_all-student.png)  
#### Post-Optimization
![CLI Result GET all-student post](profiling_result/result_cli_all-student_post.png)

## GET all-student-name
### GUI
![GUI Result GET all-student-name](profiling_result/result_gui_all-student-name.png)
### CLI
#### Pre-Optimization
![CLI Result GET all-student-name](profiling_result/result_cli_all-student-name.png)
#### Post-Optimization
![CLI Result GET all-student-name post](profiling_result/result_cli_all-student-name_post.png)

## GET highest-gpa
### GUI
![GUI Result GET highest-gpa](profiling_result/result_gui_highest-gpa.png)
### CLI
#### Pre-Optimization
![CLI Result GET highest-gpa](profiling_result/result_cli_highest-gpa.png)
#### Post-Optimization
![CLI Result GET highest-gpa post](profiling_result/result_cli_highest-gpa_post.png)  

Terdapat Improvement pada Profiling dari Jmeter setelah kita melakukan refactor pada StudentService 
untuk mengoptimalkan waktu pemanggilan API. Bisa dilihat pada kolom elapsed di gambar post-optimization 
bahwa waktu response time API telah menurun cukup signifikan.  
Kesimpulan yang saya dapat adalah profiling merupakan tools yang kuat dalam membantu kita melihat performa aplikasi kita. 
Kita dapat melihat bagian fungsi mana yang menghabiskan waktu performa sehingga kita dapat tahu dimana titik lemah kode 
kita yang sekiranya perlu direfactor.