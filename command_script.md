# SCRIPT OF COMMANDS 

## Part 1
1. whoami
2. w
3. pwd
4. homedu
5. groups
6. checkproject
7. mkdir quest_intro
8. cd quest_intro
9. pwd
10. cp /projects/intro/job-script.sh .

## Part 2
11. more job-script.sh  
12. module avail
13. module avail python

## Part 3
14. nano job-script.sh
15. more job-script.sh
16. sbatch job-script.sh
17. sacct -X
18. squeue
19. sacct -X
20. seff <job_id>
21. ls -l
22. more outlog
23. more python_output.txt
24. salloc -A <allocation_name> -p <partition_name> -t 00:10:00 -N 1 -n 1
25. ssh <allocated node>
26. w
27. top    
28. logout
29. man w
30. !sbatch
31. scancel <job_id>
