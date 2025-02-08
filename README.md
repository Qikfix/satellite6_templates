# Satellite6 Templates

# Disclaimer

This project scripts are NOT delivered and/or released by Red Hat. This is an independent project to help customers and Red Hat Support team to analyze some data, help with the troubleshooting, or implement something that is not available in the official way at the moment this one was created.

---

Adding some custom partition templates, that will help when trying to customize the disk layout

- [dynamic_partition_table_lvm_first_disk](partition_tables/dynamic_partition_table_lvm_first_disk)

Searching by the first disk, using 20G as a reference, and setting the LVM based on the configuration on this example.

- [dynamic_partition_table_lvm_second_disk](partition_tables/dynamic_partition_table_lvm_second_disk)

Searching by the second disk, using 40G as a reference, and setting the LVM based on the configuration on this example.

- [dynamic_partition_table_xfs_first_disk](partition_tables/dynamic_partition_table_xfs_first_disk)

Searching by the first disk, using 20G as a reference, and setting the XFS based on the configuration on this example.

- [dynamic_partition_table_xfs_second_disk](partition_tables/dynamic_partition_table_xfs_second_disk)

Searching by the first disk, using 40G as a reference, and setting the XFS based on the configuration on this example.


Note that in those templates, I'm using lsblk basically to identify which one should be the first disk. Feel free to use it, or any tool that would be available in that specific boot moment.

Enjoy it!