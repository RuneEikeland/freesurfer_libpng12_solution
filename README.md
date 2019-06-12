# freesurfer_libpng12_solution

A solution to incompatibility issue between Freesurfer and Ubuntu 19.04 Disco Dingo regarding libpng12.so.0 and libpng12.so.0.54.0.

Link to freesurfer software: https://surfer.nmr.mgh.harvard.edu/

# 1: Download libpng12-0_1.2.54-1ubuntu1_amd64.deb 
   


# 2: Extract libpng12-0_1.2.54-1ubuntu1_amd64.deb

   ar -xv libpng12-0_1.2.54-1ubuntu1_amd64.deb


# 3: Extract data.tar.xz
  
   tar -xJf data.tar.xz


# 4: Copy libpng12.so.0 and libpng12.so.0.54.0 from extracted folders lib/x86_64-linux-gnu/ into /usr/lib/x86_64-linux-gnu

   sudo cp lib/x86_64-linux-gnu/* /usr/lib/x86_64-linux-gnu

