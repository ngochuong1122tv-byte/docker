FROM nginx:alpine

# Xóa web mặc định của nginx
RUN rm -rf /usr/share/nginx/html/*

# Đặt thư mục làm việc
WORKDIR /usr/share/nginx/html

# Copy toàn bộ project vào
COPY . .

# Mở port 80
EXPOSE 80

# Chạy nginx
CMD ["nginx", "-g", "daemon off;"]