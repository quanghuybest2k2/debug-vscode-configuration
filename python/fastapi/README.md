# Debug Fast API with VSCode

- Bắt buộc cài extension [Python Debugger](https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy)

Note:

- Đừng chạy lệnh `uvicorn main:app --reload` thủ công, vì sẽ gây debug không nhận được thông tin.

- Chỉ cần đặt `breakpoint` tại dòng cần debug, rồi Start Debugging (F5) trong vs code.

- Không nên đặt debug ở hàm => debug sẽ ko chạy từng dòng.

