# Useful functions



`TASK_DESC * taskInfoGet (int taskid) `

> Returns useful user informations

`WIND_TCB * taskTCB(int taskid)`: 

> returns pointer to task control block

`int taskIdListGet (int idList[],int max_tasks)`

> idList is taskArray to be filled in
>
> max_tasks is upper bound of idList array
>
> returns the numbers of tasks filled







# structures



struct TASK_DESC  task_name, task_id and some other useful end user information



struct WIND_TCB holds useful backend information

