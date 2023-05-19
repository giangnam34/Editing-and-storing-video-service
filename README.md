Nhóm 4: Phát triển service xử lý, lưu trữ video
Thành viên:
Võ Giang Nam 20110680
Lường Đại Nghĩa 20110682
Giao diện swagger của project
![image](https://github.com/giangnam34/Editing-and-storing-video-service/assets/81871052/6e019557-7d75-475b-b2d8-d2e22a271ee3)

Các tính năng hiện có của project:
**List of projects**
**Upload video file and create new project for it**
**Merge two videos together**
**Delete project from db and related files from a storage**
**Retrieve project details**
**Edit project's video**
**Change speed of video**
**Convert video to AVI format**
**Duplicate project**
**Extract audio from a video**
**Get preview thumbnail file**
**Get timeline thumbnail file**
**Get video stream**
**Get or create thumbnail for preview or thumbnails for timeline**
**Upload custom preview thumbnail**

**Làm thế nào để cài đặt và chạy project**
**Đối với cách chạy trực tiếp trên Windows:
Yêu cầu phần mềm để chạy project**
Python (>= 3.6)
FFmpeg
MongoDB
RabbitMQ (celery backend)
**Để chạy project**
# clone project
git clone https://github.com/giangnam34/Editing-and-storing-video-service.git

# install and run video server for development
# NOTE: your virtualenv must be activated
pip install -e video-server/[dev]
cd video-server/src
python -m videoserver.app
**Đối với docker**
git clone https://github.com/giangnam34/Editing-and-storing-video-service.git
cd Editing-and-storing-video-service
docker-compose up -d
