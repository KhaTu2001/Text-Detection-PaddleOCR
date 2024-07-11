pip install .
pip install paddleocr --upgrade
pip install paddlepaddle

nếu chạy GPU thì chúng ta thay use_gpu trong file DBNet.yml thành true và chạy lệnh 
pip install paddlepaddle-gpu
Nếu không chạy với GPU thì bỏ qua câu lệnh trên trên

pip install -r requirements.txt
python tools/train.py -c DBNet.yml