# otp-2.0
def print_preview(self):         dialog = qtps.QPrintPreviewDialog(self.printer, self)         dialog.paintRequested.connect(self._print_document)         dialog.exec()         self._update_preview_size() 
