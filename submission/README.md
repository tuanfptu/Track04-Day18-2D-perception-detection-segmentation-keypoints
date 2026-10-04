# Bai nop Lab 18

- Ho ten: Ha Manh Tuan (Hà Mạnh Tuân)
- Ma sinh vien: 2A202602982
- Notebook da chay: `../lab_2d_perception_student.ipynb`
- Ket qua: `ket_qua.json`; nhan YOLO-seg: `autolabel/bus.txt`

Notebook da chay 40 epoch tren GPU (imgsz 640), hoan thanh 12/12 cau hoi va tat ca phep kiem tra bat buoc. Pose mAP50-95 tren val goc cua model flip_idx giai phau la 0.4505.

## Phan 4C

| Model | Val goc | Val lat guong |
| --- | ---: | ---: |
| Flip_idx giai phau | 0.4505 | 0.3959 |
| Flip_idx dong nhat | 0.4287 | 0.2981 |

Val goc che bot loi flip_idx: chenh lech giua hai model chi 0.0218 mAP, trong khi val lat guong cho thay chenh lech 0.0978. Tap val goc chi co ho quay theo mot huong, nen can bo sung anh quay huong con lai va anh lat guong voi nhan keypoint dung quy uoc giai phau.
