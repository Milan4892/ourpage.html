[register.html](https://github.com/user-attachments/files/23117636/register.html)
[Uploading image…]()[login.html](https://github.com/user-attachments/files/23117645/login.html)
[register.html](https://github.com/user-attachments/files/23117647/register.html)[home.html](https://github.com/user-attachments/files/23117654/home.html)
[login.html](https://github.com/user-attachments/files/23117656/login.html)[register.html](https://github.com/user-attachments/files/23117658/register.html)
[dash.html](https://github.com/user-attachments/files/23117668/dash.html)
<!doctype html>
<html lang="en">
  <head>
    <!-- Meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <title>Dashboard - MySite</title>
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar navbar-dark bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand fw-bold" href="#">My Dashboard</a>
      </div>
    </nav>

    <div class="container-fluid">
      <div class="row">
        <!-- Sidebar -->
        <nav class="col-md-3 col-lg-2 d-md-block bg-light sidebar collapse p-3">
          <h5 class="fw-bold">Menu</h5>
          <ul class="nav flex-column">
            <li class="nav-item"><a class="nav-link active" href="home.html">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="login.html">Login</a></li>
            <li class="nav-item"><a class="nav-link" href="register.html">Register</a></li>
            <li class="nav-item"><a class="nav-link" href="dash.html">Dashboard</a></li>
          </ul>
        </nav>

        <!-- Main Content -->
        <main class="col-md-9 ms-sm-auto col-lg-10 px-md-4 py-4">
          <h2 class="fw-bold mb-4">Dashboard Overview</h2>

          <!-- Stats Cards -->
          <div class="row mb-4">
            <div class="col-md-3">
              <div class="card text-center shadow-sm p-3">
                <h5>Total Users</h5>
                <p class="display-6 fw-bold">1,245</p>
              </div>
            </div>
            <div class="col-md-3">
              <div class="card text-center shadow-sm p-3">
                <h5>Sales</h5>
                <p class="display-6 fw-bold">$8,930</p>
              </div>
            </div>
            <div class="col-md-3">
              <div class="card text-center shadow-sm p-3">
                <h5>Orders</h5>
                <p class="display-6 fw-bold">320</p>
              </div>
            </div>
            <div class="col-md-3">
              <div class="card text-center shadow-sm p-3">
                <h5>Messages</h5>
                <p class="display-6 fw-bold">27</p>
              </div>
            </div>
          </div>

          <!-- Table Section -->
          <div class="card shadow-sm">
            <div class="card-header fw-bold">Recent Activities</div>
            <div class="card-body">
              <table class="table table-striped">
                <thead>
                  <tr>
                    <th>Date</th>
                    <th>Activity</th>
                    <th>Status</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>2025-09-30</td>
                    <td>User registered</td>
                    <td><span class="badge bg-success">Completed</span></td>
                  </tr>
                  <tr>
                    <td>2025-09-29</td>
                    <td>Order #4321 placed</td>
                    <td><span class="badge bg-info">Pending</span></td>
                  </tr>
                  <tr>
                    <td>2025-09-28</td>
                    <td>Password changed</td>
                    <td><span class="badge bg-warning">Review</span></td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </main>
      </div>
    </div>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <a href="home.html" class="btn btn-primary">Back to Home</a>
  </body>
</html>

