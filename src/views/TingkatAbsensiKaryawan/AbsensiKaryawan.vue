<template>
<div class="container">
  <div class="row">
    <div class="col-md-12 mt-4">
    <!-- Responsive Table -->
              <div class="card">


                <div class="card-header d-flex align-items-center justify-content-between">
                  <h5 class="mb-0">Tingkat Absensi Karyawan</h5>
                  <router-link type="button" to="/tambah-absensi-karyawan" class="btn btn-sm btn-primary"><i class='bx bx-plus me-1' ></i> Tambah Baru</router-link>
                  <!-- <small class="text-muted float-end">Company Profile Igmma</small> -->
                </div>

                
                <!-- FILTER --> 
                  <form action="">
                    <div class="row justify-content-end">             
                    <div class="me-4 mb-4 col-md-4 d-flex align-items-end justify-content-beetwen">
                        <label class="col-sm-4 col-form-label" for="filterTahun">Filter Tahun</label>
                          <select name="filterTahun" id="filterTahun" class="form-control">
                            <optgroup>
                              <option value="">Pilih Bulan</option>
                              <option value="2021">2021</option>
                              <option value="2022">2022</option>
                            </optgroup>
                      </select>
                    </div>
                    <div class="me-4 mb-4 col-md-4 d-flex align-items-end justify-content-beetwen">
                        <label class="col-sm-4 col-form-label" for="filterBulan">Filter Bulan</label>
                          <select name="filterBulan" id="filterBulan" class="form-control">
                            <optgroup>
                              <option value="">Pilih Tahun</option>
                              <option value="Januari">Januari</option>
                              <option value="Februari">Februari</option>
                            </optgroup>
                      </select>
                    </div>
                    </div>
                  </form>

                <!-- END FILTER -->

                <!-- <h5 class="card-header">Responsive Table</h5> -->
                <div class="table-responsive text-nowrap">
                  <table class="table">
                    <thead>
                      <tr class="text-nowrap">
                        <th>No</th>
                        <th>Bulan</th>
                        <th>Jumlah Kehadiran</th>
                        <th>Jml Tanpa Keterangan</th>
                        <th>jml Sakit</th>
                        <th>jml Ijin</th>
                        <th>Presentase Absensi</th>
                        <th>Action</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">1</th>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>
                            <div class="btn-group" role="group" aria-label="Basic example">
                              <button type="button" class="btn btn-xs btn-outline-primary" title="View"><i class='bx bx-detail'></i></button>
                              <router-link  type="button" class="btn btn-xs btn-outline-primary" to="/edit-absensi-karyawan" title="Edit"><i class='bx bx-edit'></i></router-link>
                              <button type="button" class="btn btn-xs btn-outline-primary" title="Delete"><i class='bx bxs-trash'></i></button>
                            </div>
                        </td>
                      </tr>
                      <tr>
                        <th scope="row">2</th>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>
                          <div class="btn-group" role="group" aria-label="Basic example">
                              <button type="button" class="btn btn-xs btn-outline-primary" title="View"><i class='bx bx-detail'></i></button>
                              <router-link  type="button" class="btn btn-xs btn-outline-primary" to="/edit-absensi-karyawan" title="Edit"><i class='bx bx-edit'></i></router-link>
                              <button type="button" class="btn btn-xs btn-outline-primary" title="Delete"><i class='bx bxs-trash'></i></button>
                          </div>
                        </td>
                      </tr>
                      <tr>
                        <th scope="row">3</th>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>Table cell</td>
                        <td>
                          <div class="btn-group" role="group" aria-label="Basic example">
                              <button type="button" class="btn btn-xs btn-outline-primary" title="View"><i class='bx bx-detail'></i></button>
                              <router-link  type="button" class="btn btn-xs btn-outline-primary" to="/edit-absensi-karyawan" title="Edit"><i class='bx bx-edit'></i></router-link>
                              <button type="button" class="btn btn-xs btn-outline-primary" title="Delete"><i class='bx bxs-trash'></i></button>
                          </div>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
              <!--/ Responsive Table -->
    </div>
  </div>
</div>
</template>