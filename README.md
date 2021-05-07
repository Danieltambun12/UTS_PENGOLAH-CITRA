# UTS_PENGOLAH-CITRA

![2021-05-07 (1)](https://user-images.githubusercontent.com/56190893/117488890-20ca8d80-af97-11eb-9ad0-18f70bd3e9aa.png)

![2021-05-07 (2)](https://user-images.githubusercontent.com/56190893/117488899-22945100-af97-11eb-95ec-f571ea910176.png)

![2021-05-07 (3)](https://user-images.githubusercontent.com/56190893/117488907-232ce780-af97-11eb-97ae-6db7b8406c15.png)

# kodingnnya yaitu :

[filename, pathname] = uigetfile({'.png','.png'}); gambar1 =imread([pathname, filename]);

axes(handles.axes1); 
imshow(gambar1);

R = gambar1(:,:,1); 
G = gambar1(:,:,2); 
B = gambar1(:,:,3);

Red = cat(3,R,G0,B0); 
Green = cat(3,R0,G,B0); 
Blue = cat(3,R0,G0,B);

axes(handles.axes2); 
imshow(Red);

axes(handles.axes3); 
imshow(Green);

axes(handles.axes4); 
imshow(Blue);

