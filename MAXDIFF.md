# MAXDIFF

Cho một dãy số nguyên a gồm n phần tử. Các phần tử trong dãy được sắp xếp theo trình tự tăng dần, tức là ai ≤ ai+1 với mọi 1 ≤ i < n.

Ta định nghĩa độ đẹp của dãy a là khoảng cách lớn nhất giữa hai phần tử liên tiếp bất kì trong dãy. Nói cách khác, độ đẹp của dãy a là giá trị ai − a(i−1) lớn nhất với mọi 2 ≤ i ≤ n.

Hãy xóa một phần tử bất kì trong dãy A sao cho độ đẹp của dãy nhận được là lớn nhất có thể.

## Dữ liệu

- Dòng đầu tiên gồm số nguyên n (3 ≤ n ≤ 1000) - số phần tử trong dãy.
- Dòng thứ hai gồm n số nguyên a1, a2, . . . , an (1 ≤ ai ≤ 109) - số phần tử trong dãy.

## Kết quả

- In ra độ đẹp lớn nhất của dãy a sau khi xóa đi một phần tử bất kì.

## Ví dụ

| Input                  |Output   |
|---                      |---           |
| 4                        | 3
 |2 4 5 6                  |

## Giải thích

- Ta sẽ xóa đi phần tử thứ 2 trong dãy a. Dãy sau khi xóa là [2, 5, 6] và có độ đẹp là 3.
