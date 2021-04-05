# reseachDocker

- xem cac image: docker images
- pull 1 image tu hub.docker: docker pull image:tag
- remove image: docker rm [id] (or [image_name])
- chay 1 image: docker run -it --name "[container_name]" -h "[host_name]" image
	+ -i khi container tao ra se nhan tuong tac
	+ -t container ket noi voi terminal
	+ -it la viet gop lai cua -i va -t
	+ --name la ten container
	+ -h la host name
- out ra main cmd nhung cac image van chay: CTRL + P, CTRL + Q
- xem cac container dang chay: docker ps
- dung container lai: docker stop [container_name]
- khi dang o ngoai main cmd nhung muon tro lai 1 container nao do: docker attach [container_name] (or [container_id])
- khi muon xoa 1 container: docker rm [container_name]
- xoa 1 container dang chay: docker rm [container_name] -f
- xem tat ca cac container dang chay: docker ps -a
 
 
 --------LINUX CMD------
 build service: (sudo) docker-compose up -d
 
 tạo file mới: touch filename
 
 
 -------------
