# SCRIPT OF COMMANDS 

## Part 1
whoami
w
pwd
homedu
groups
checkproject
mkdir quest_intro
cd quest_intro
pwd
cp /projects/intro/job-script.sh .

## Part 2
more job-script.sh  
	what does it do once it gets on the node?
module avail
module avail python

## Part 3
nano job-script.sh
	control-x to exit
more job-script.sh
sbatch job-script.sh
sacct -X
squeue
sacct -X
(when the job is complete)
seff <job_id>
ls -l
more outlook
more python_output.txt
salloc -A <allocation_name> -p <partition_name> -t 00:10:00 -N 1 -n 1
ssh <allocated node>
w
top    
	q to exit
logout
man w
	q to exit
!sbatch
scancel <job_id>