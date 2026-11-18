cmake_minimum_required(VERSION 4.0)
project(Sekaiju LANGUAGES C CXX)

find_package(MFC REQUIRED)

add_executable(Sekaiju WIN32)

target_sources(Sekaiju
    PRIVATE
        src/AboutDlg.cpp
        src/AutoSaveDlg.cpp
        src/ChildFrame.cpp
        src/ColorfulCheckListBox.cpp
        src/ColorfulComboBox.cpp
        src/ColorOptionPage.cpp
        src/ColorSelectComboBox.cpp
        src/common.c
        src/ControlChangeListBox.cpp
        src/EditBeatScanDlg.cpp
        src/EditBreakupAndTrillDlg.cpp
        src/EditChannelDlg.cpp
        src/EditDurationDlg.cpp
        src/EditInsertMeasureDlg.cpp
        src/EditKeyDlg.cpp
        src/EditQuantizeDlg.cpp
        src/EditRemoveMeasureDlg.cpp
        src/EditStrokeDlg.cpp
        src/EditTempoDlg.cpp
        src/EditTimeDlg.cpp
        src/EditTimeSmpDlg.cpp
        src/EditTrackDlg.cpp
        src/EditValueDlg.cpp
        src/EditVelocityDlg.cpp
        src/EventKindListBox.cpp
        src/EventListFrame.cpp
        src/EventListIndexPropertyView.cpp
        src/EventListIndexScaleView.cpp
        src/EventListOptionPage.cpp
        src/EventListPrintView.cpp
        src/EventListPropertyScaleView.cpp
        src/EventListScaleView.cpp
        src/FilePropertyDlg.cpp
        src/FontOptionPage.cpp
        src/GeneralOptionPage.cpp
        src/GraphKindListBox.cpp
        src/HistoryRecord.cpp
        src/HistoryUnit.cpp
        src/InplaceEdit.cpp
        src/InplaceListBox.cpp
        src/LanguageDlg.cpp
        src/MainFrame.cpp
        src/MetronomeDlg.cpp
        src/MIDIDeviceSheet.cpp
        src/MIDIInDevicePage.cpp
        src/MIDIInstDefDrumPage.cpp
        src/MIDIInstDefNormPage.cpp
        src/MIDIInSyncModePage.cpp
        src/MIDIOutDevicePage.cpp
        src/MIDIOutSyncModePage.cpp
        src/MIDISyncModeSheet.cpp
        src/MIDIThruPage.cpp
        src/MusicalScoreFrame.cpp
        src/MusicalScoreOptionPage.cpp
        src/MusicalScorePrintView.cpp
        src/MusicalScoreScaleView.cpp
        src/MusicalScoreTimeScaleView.cpp
        src/MusicalScoreTrackScaleView.cpp
        src/MusicalScoreTrackTimeView.cpp
        src/OptionSheet.cpp
        src/PianoRollFrame.cpp
        src/PianoRollKeyScaleView.cpp
        src/PianoRollKeyTimeView.cpp
        src/PianoRollOptionPage.cpp
        src/PianoRollPrintView.cpp
        src/PianoRollScaleView.cpp
        src/PianoRollTimeScaleView.cpp
        src/PianoRollVelScaleView.cpp
        src/PianoRollVelTimeView.cpp
        src/PropertyKeySignatureDlg.cpp
        src/PropertyMarkerDlg.cpp
        src/PropertyNoteDlg.cpp
        src/PropertyTempoDlg.cpp
        src/PropertyTimeSignatureDlg.cpp
        src/Sekaiju.rc
        src/SekaijuApp.cpp
        src/SekaijuDoc.cpp
        src/SekaijuDocManager.cpp
        src/SekaijuDocTemplate.cpp
        src/SekaijuFileDlg.cpp
        src/SekaijuPreviewView.cpp
        src/SekaijuStatusBar.cpp
        src/SekaijuToolBar.cpp
        src/SekaijuView.cpp
        src/SelectVoiceDlg.cpp
        src/stdafx.cpp
        src/TextFile.cpp
        src/TrackListBox.cpp
        src/TrackListFrame.cpp
        src/TrackListModeScaleView.cpp
        src/TrackListOption1Page.cpp
        src/TrackListOption2Page.cpp
        src/TrackListPrintView.cpp
        src/TrackListScaleView.cpp
        src/TrackListTimeScaleView.cpp
        src/TrackListTrackModeView.cpp
        src/TrackListTrackScaleView.cpp
        src/TrackListTrackTimeView.cpp
)

set_target_properties(Sekaiju PROPERTIES
    MSVC_RUNTIME_LIBRARY ""
    MSVC_RUNTIME_CHECKS ""
    CMAKE_MFC_FLAG ""
    COMPILE_WARNING_AS_ERROR ""
    LINK_WARNING_AS_ERROR ""
)

