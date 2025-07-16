<!-- <script>
  import { Header } from "$lib/components/ui/alert-dialog";

</script> -->
<!-- <script>
    const {children} = $props()
</script>

HELLO
{@render children?.()} -->
<!-- <Header>
    <h1>ข้อมูลผู้ยืมของ</h1>

</Header> -->
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>ฟอร์มยืมของ CS Media</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
    }

    .header {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo {
      width: 60px;
    }

    .nav {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
      border-bottom: 2px solid #ccc;
    }

    .nav div {
      padding: 10px 20px;
      cursor: pointer;
    }

    .nav .active {
      background-color: #f7941d;
      color: white;
      border-radius: 15px 15px 0 0;
      font-weight: bold;
    }

    .form-section {
      margin-top: 30px;
    }

    .form-row {
      display: flex;
      gap: 20px;
      margin-bottom: 20px;
    }

    .form-group {
      flex: 1;
      display: flex;
      flex-direction: column;
    }

    label {
      margin-bottom: 5px;
      font-weight: bold;
    }

    input {
      padding: 10px;
      border: none;
      border-radius: 10px;
      background-color: #ccc;
    }

    .button-row {
      display: flex;
      justify-content: center;
      margin-top: 30px;
    }

    .next-button {
      background-color: #f7941d;
      color: white;
      border: none;
      padding: 15px 40px;
      font-size: 18px;
      border-radius: 12px;
      cursor: pointer;
    }

    .next-button:hover {
      background-color: #e7840d;
    }
  </style>
</head>
<body>
  <div class="container">

    <div class="nav">
      <div class="active">ข้อมูลผู้ยืม</div>
      <div>ข้อมูลขอยืม</div>
      <div>ของที่จะยืม</div>
      <div>วันคืนของ</div>
    </div>

    <div class="form-section">
      <div class="form-row">
        <div class="form-group">
          <label>ชื่อจริง</label>
          <input type="text">
        </div>
        <div class="form-group">
          <label>นามสกุล</label>
          <input type="text">
        </div>
        <div class="form-group">
          <label>รหัสนักศึกษา</label>
          <input type="text">
        </div>
        <div class="form-group">
          <label>ชื่อเล่น</label>
          <input type="text">
        </div>
      </div>

      <div class="form-row">
        <div class="form-group">
          <label>ชั้นปี</label>
          <input type="text">
        </div>
        <div class="form-group">
          <label>ชื่อดิสในห้องมีเดีย</label>
          <input type="text">
        </div>
        <div class="form-group">
          <label>ช่องทางการติดต่ออื่นๆ</label>
          <input type="text">
        </div>
        <div class="form-group">
          <label>เบอร์โทรศัพท์</label>
          <input type="text">
        </div>
      </div>

      <div class="button-row">
        <button class="next-button">NEXT</button>
      </div>
    </div>
  </div>
</body>
</html>
