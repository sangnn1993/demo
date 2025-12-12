# Sử dụng image Nginx Alpine nhẹ
FROM nginx:alpine

# Copy file HTML vào thư mục web root của Nginx
COPY index2.html /usr/share/nginx/html/index.html

# Expose port 80 (mặc định cho HTTP)
EXPOSE 80

# Khởi động Nginx (mặc định)
CMD ["nginx", "-g", "daemon off;"]