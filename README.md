# nguoi-giao-hang
Đường đi của người giao hàng (TSP)
void TSP() {

            /*E là tập hợp các cạnh, Chu_trinh là tập hợp các cạnh được chọn để đưa vào chu trình,

            mở đầu Chu_trinh rỗng*/

            /*Sắp xếp các cạnh trong E theo thứ tự tăng của độ dài*/

            Chu_Trinh = F;

            Gia = 0.0;

            while (E != F) {

                        if (cạnh e có thể chọn) {

                                    Chu_Trinh = Chu_Trinh + [e];

                                    Gia = Gia + độ dài của e;

                        }

                        E := E-[e];

            }

}
