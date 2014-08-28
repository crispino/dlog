dlog
====

the dlog used for printing debug information.

Feature:
    Rotate function

Usage:
  1.debug file init
    int debug_open_file(const char *path);
  2.debug file deinit
    void debug_close_file(void);
  3.output to file
    void debug_printf(int level, const char *fmt, ...);

Set the Properties of File:
  int set_max_file_size(unsigned int size);
  int get_max_file_size(void);
  int set_backup_file_num(int num);
  int get_backup_file_num(void);
  int set_debug_level(int level);
  int get_debug_level(void);
