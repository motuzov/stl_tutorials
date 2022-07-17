# stl_tutorials
Learning of Statistical Learning Theory

docker pull jupyter/scipy-notebook:latest  
Set env variables in powershell  
$env:var_name = '<var_val>'  
docker create --name stl_tutorials -p 10000:8888 -v C:\Users\motuz\education\stl_tutorials:/home/jovyan/work -v C:\Users\motuz\education\data:/home/jovyan/data  jupyter/scipy-notebook:latest  
