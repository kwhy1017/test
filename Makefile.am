CFLAGS			= @CFLAGS@ -I../include -I./include

SUBDIRS			= main memo calendar
bin_PROGRAMS	= diary
diary_SOURCES	= diary.h main/main.c memo/memo.c calendar/calendar.c

lib_LIBRARIES	= libmydiary.a
libmydiary_a_SOURCES	= diary.h memo/memo.c calendar/calendar.c

clean	:
		rm -rf *.o *.a diary
		@echo 모든 파일을 지웠습니다.
