<template>
<nav class="main-header navbar navbar-expand-md navbar-light navbar-white">

    <div class="container">
     
      
      <button class="navbar-toggler order-1" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse order-3" id="navbarCollapse">
        <!-- Left navbar links -->
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" data-widget="pushmenu" href="#" role="button"><i class="fa fa-bars"></i></a>
          </li>
     
 
                </ul>
              </li>  
              <!-- End Level two -->
            </ul>
          </li>

        </ul>

       
      </div>

      <!-- Right navbar links -->
      <ul class="order-1 order-md-3 navbar-nav navbar-no-expand ml-auto">
        <!-- Messages Dropdown Menu -->
       
        <!-- Notifications Dropdown Menu -->
        <li class="nav-item dropdown">
          <a class="nav-link" data-toggle="dropdown" href="#">
            <i class="fa fa-bell"></i>
            <span class="badge  badge-danger navbar-badge">15</span>
          </a>

          <!-- modal -->
          <div class="dropdown-menu dropdown-menu-lg dropdown-menu-right">
            <!-- header -->
            <span class="dropdown-header">15 Notifications</span>

             <!-- item notif -->
            <div class="dropdown-divider"></div>
            <a href="#" class="dropdown-item">
              <i class="fa fa-envelope mr-2"></i> 4 new messages
              <span class="float-right text-muted text-sm">3 mins</span>
            </a> 
            <div class="dropdown-divider"></div>
            <a href="#" class="dropdown-item dropdown-footer">See All Notifications</a>
          </div>

        </li>
        <li class="nav-item">
          <a class="nav-link" data-widget="control-sidebar" data-slide="true" href="#" role="button"><i
              class="fa fa-th-large"></i></a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default { 
}
</script>