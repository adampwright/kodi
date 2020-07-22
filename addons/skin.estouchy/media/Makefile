TARGET=Textures.xbt

all: $(TARGET)

.PHONY: force

$(TARGET):
	/build/kodi-0YFpDP/kodi-17.6+dfsg1/tools/depends/native/TexturePacker/bin/TexturePacker -dupecheck -input . -output $(TARGET)

clean:
	rm -f $(TARGET)

distclean: clean

