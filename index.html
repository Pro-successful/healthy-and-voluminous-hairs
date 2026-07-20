avaScript




import React, { useState } from 'react';
import { StyleSheet, Text, View, Image, TouchableOpacity, ScrollView, TextInput, Alert } from 'react-native';

export default function AdvancedHairApp() {
  const [currentTab, setCurrentTab] = useState('analyze'); // analyze, tracker, scanner
  const [step, setStep] = useState('welcome'); // welcome, input, results
  const [barcodeText, setBarcodeText] = useState('');
  const [scannedProductInfo, setScannedProductInfo] = useState(null);

  // Mock Analysis Results including New Feature Metrics
  const mockAnalysis = {
    volumeScore: 58,
    porosity: 'High Porosity (Absorbs quickly, loses moisture instantly)',
    waterRisk: 'High Hardness detected in your area (Mineral buildup flattening roots)',
    routine: [
      { name: 'Apple Cider Vinegar Scalp Rinse', function: 'Removes local hard water mineral weight' },
      { name: 'Hydrolyzed Rice Protein Spray', function: 'Plumps cortex structure for immediate 20% visual thickness' }
    ]
  };

  // Ingredient Database Simulation for Feature 2
  const handleIngredientCheck = () => {
    const product = barcodeText.trim().toLowerCase();
    if (product.includes('sulfate') || product.includes('dmdm')) {
      setScannedProductInfo({
        status: 'Unsafe for Volume',
        color: '#E74C3C',
        reason: 'Contains heavy surfactants that strip natural moisture, causing the scalp to overproduce oils that flatten roots.'
      });
    } else {
      setScannedProductInfo({
        status: 'Volume Approved',
        color: '#2ECC71',
        reason: 'Clean formula. Formulated with lightweight humectants that expand hair fiber diameter safely.'
      });
    }
  };

  return (
    <View style={styles.container}>
      {/* APP TITLE BAR */}
      <View style={styles.appBar}>
        <Text style={styles.appTitle}>StrandAI Pro</Text>
        <Text style={styles.appBadge}>AI Trichologist</Text>
      </View>

      {/* CORE SCREENS BASED ON NAVIGATION TAB */}
      <ScrollView contentContainerStyle={styles.mainScroll}>
        
        {/* TAB 1: AI HAIR DIAGNOSIS & ENVIRONMENTAL ANALYSIS */}
        {currentTab === 'analyze' && (
          <View>
            {step === 'welcome' && (
              <View style={styles.heroSection}>
                <Text style={styles.sectionHeader}>Scan & Diagnose Strands</Text>
                <Text style={styles.bodyText}>Analyze cuticles, local water mineral density, and current baseline volume score.</Text>
                <TouchableOpacity style={styles.actionButton} onPress={() => setStep('results')}>
                  <Text style={styles.actionButtonText}>Launch Smart Scan</Text>
                </TouchableOpacity>
              </View>
            )}

            {step === 'results' && (
              <View>
                <Text style={styles.sectionHeader}>🔬 Structural Diagnostic Report</Text>
                
                <View style={styles.metricRow}>
                  <View style={styles.metricBlock}>
                    <Text style={styles.metricLabel}>Volume Score</Text>
                    <Text style={styles.metricVal}>{mockAnalysis.volumeScore}%</Text>
                  </View>
                  <View style={styles.metricBlock}>
                    <Text style={styles.metricLabel}>Porosity Type</Text>
                    <Text style={[styles.metricVal, { fontSize: 14 }]}>High</Text>
                  </View>
                </View>

                {/* Environmental Awareness Card */}
                <View style={[styles.alertCard, { borderColor: '#E67E22' }]}>
                  <Text style={styles.alertTitle}>📍 Regional Water Quality Impact</Text>
                  <Text style={styles.alertBody}>{mockAnalysis.waterRisk}</Text>
                </View>

                <Text style={styles.subHeader}>Targeted Thickening Routine</Text>
                {mockAnalysis.routine.map((item, index) => (
                  <View key={index} style={styles.routineItem}>
                    <Text style={styles.routineName}>{item.name}</Text>
                    <Text style={styles.routineDesc}>{item.function}</Text>
                  </View>
                ))}

                <TouchableOpacity style={styles.backButton} onPress={() => setStep('welcome')}>
                  <Text style={styles.backButtonText}>Re-Scan Strands</Text>
                </TouchableOpacity>
              </View>
            )}
          </View>
        )}

        {/* TAB 2: INGREDIENT & BARCODE SCANNER */}
        {currentTab === 'scanner' && (
          <View style={styles.paddedContent}>
            <Text style={styles.sectionHeader}>Ingredient & Product Scanner</Text>
            <Text style={styles.bodyText}>Type an ingredient or paste a product formulation composition list below to check for follicle-clogging chemicals.</Text>
            
            <TextInput 
              style={styles.inputField}
              placeholder="e.g. Sodium Lauryl Sulfate, Biotin, Dimethicone"
              value={barcodeText}
              onChangeText={setBarcodeText}
            />

            <TouchableOpacity style={styles.actionButton} onPress={handleIngredientCheck}>
              <Text style={styles.actionButtonText}>Verify Product Safety</Text>
            </TouchableOpacity>

            {scannedProductInfo && (
              <View style={[styles.scannerResult, { backgroundColor: scannedProductInfo.color + '15', borderColor: scannedProductInfo.color }]}>
                <Text style={[styles.resultStatus, { color: scannedProductInfo.color }]}>{scannedProductInfo.status}</Text>
                <Text style={styles.resultReason}>{scannedProductInfo.reason}</Text>
              </View>
            )}
          </View>
        )}

        {/* TAB 3: VISUAL PROGRESS TRACKER */}
        {currentTab === 'tracker' && (
          <View style={styles.paddedContent}>
            <Text style={styles.sectionHeader}>Growth & Density Tracker</Text>
            <Text style={styles.bodyText}>Compare root density metrics and hairline fullness across your personal care timeline.</Text>
            
            {/* Visual Timeline Split Simulation */}
            <View style={styles.timelineContainer}>
              <View style={styles.timelineColumn}>
                <Text style={styles.timelineDate}>Baseline (Month 0)</Text>
                <View style={[styles.mockPhoto, { backgroundColor: '#E2E8F0' }]}>
                  <Text style={styles.photoText}>Density: Flat{"\n"}Score: 42%</Text>
                </View>
              </View>
              <View style={styles.timelineColumn}>
                <Text style={styles.timelineDate}>Current (Month 2)</Text>
                <View style={[styles.mockPhoto, { backgroundColor: '#D6E4FF' }]}>
                  <Text style={styles.photoText}>Density: Active{"\n"}Score: 58%</Text>
                </View>
              </View>
            </View>

            <View style={styles.progressSummary}>
              <Text style={styles.summaryTitle}>🎉 Realized Improvements</Text>
              <Text style={styles.summaryText}>Your hair crown density expanded by **16%** since incorporating the recommended protein solutions.</Text>
            </View>
          </View>
        )}

      </ScrollView>

      {/* CORE BOTTOM NAVIGATION BAR */}
      <View style={styles.bottomNav}>
        <TouchableOpacity style={[styles.navItem, currentTab === 'analyze' && styles.activeNavItem]} onPress={() => setCurrentTab('analyze')}>
          <Text style={[styles.navText, currentTab === 'analyze' && styles.activeNavText]}>🔬 Diagnostics</Text>
        </TouchableOpacity>
        
        <TouchableOpacity style={[styles.navItem, currentTab === 'scanner' && styles.activeNavItem]} onPress={() => setCurrentTab('scanner')}>
          <Text style={[styles.navText, currentTab === 'scanner' && styles.activeNavText]}>🧪 Bio-Check</Text>
        </TouchableOpacity>
        
        <TouchableOpacity style={[styles.navItem, currentTab === 'tracker' && styles.activeNavItem]} onPress={() => setCurrentTab('tracker')}>
          <Text style={[styles.navText, currentTab === 'tracker' && styles.activeNavText]}>📈 Progress</Text>
        </TouchableOpacity>
      </View>
    </View>
  );
}

const styles = StyleSheet.create({
  container: { flex: 1, backgroundColor: '#FAF9F6' },
  appBar: { paddingTop: 60, paddingBottom: 15, paddingHorizontal: 20, backgroundColor: '#FFF', flexDirection: 'row', justifyContent: 'space-between', alignItems: 'center', borderBottomWidth: 1, borderColor: '#F1F2F6' },
  appTitle: { fontSize: 20, fontWeight: '800', color: '#2C3436' },
  appBadge: { backgroundColor: '#6C5CE7', color: '#FFF', fontSize: 11, paddingHorizontal: 8, paddingVertical: 4, borderRadius: 8, fontWeight: '700' },
  mainScroll: { padding: 20, paddingBottom: 100 },
  paddedContent: { width: '100%' },
  heroSection: { alignItems: 'center', marginTop: 40 },
  sectionHeader: { fontSize: 22, fontWeight: '700', color: '#2D3436', marginBottom: 8 },
  subHeader: { fontSize: 16, fontWeight: '700', color: '#2D3436', marginTop: 25, marginBottom: 12 },
  bodyText: { fontSize: 14, color: '#636E72', textAlign: 'center', lineHeight: 22, marginBottom: 25 },
  actionButton: { backgroundColor: '#6C5CE7', paddingVertical: 14, width: '100%', borderRadius: 12, alignItems: 'center', marginVertical: 10 },
  actionButtonText: { color: '#FFF', fontSize: 15, fontWeight: '600' },
  backButton: { alignment: 'center', marginTop: 30, padding: 10 },
  backButtonText: { color: '#6C5CE7', textAlign: 'center', fontWeight: '600' },
  
  /* Metric UI Styling */
  metricRow: { flexDirection: 'row', justifyContent: 'space-between', marginVertical: 15 },
  metricBlock: { width: '48%', backgroundColor: '#FFF', padding: 16, borderRadius: 12, borderWidth: 1, borderColor: '#EEF0F2', alignItems: 'center' },
  metricLabel: { fontSize: 12, color: '#A0AEC0', marginBottom: 4, fontWeight: '600' },
  metricVal: { fontSize: 24, fontWeight: '800', color: '#2D3436' },
  
  /* Feature Specific Card Interfaces */
  alertCard: { backgroundColor: '#FFFEEB', borderWidth: 1, padding: 16, borderRadius: 12, marginVertical: 10 },
  alertTitle: { fontSize: 14, fontWeight: '700', color: '#D35400', marginBottom: 4 },
  alertBody: { fontSize: 13, color: '#57606F', lineHeight: 18 },
  routineItem: { backgroundColor: '#FFF', padding: 14, borderRadius: 10, marginBottom: 10, borderWidth: 1, borderColor: '#E2E8F0' },
  routineName: { fontSize: 15, fontWeight: '600', color: '#2D3436' },
  routineDesc: { fontSize: 13, color: '#747D8C', marginTop: 2 },
  
  /* Input & Product Analysis Engine Elements */
  inputField: { backgroundColor: '#FFF', borderWidth: 1, borderColor: '#DFE6E9', padding: 14, borderRadius: 10, width: '100%', fontSize: 14, marginBottom: 10 },
  scannerResult: { borderWidth: 1, borderRadius: 12, padding: 16, marginTop: 20 },
  resultStatus: { fontSize: 16, fontWeight: '700', marginBottom: 6 },
  resultReason: { fontSize: 13, color: '#2C3436', lineHeight: 19 },
  
  /* Timeline Elements */
  timelineContainer: { flexDirection: 'row', justifyContent: 'space-between', marginVertical: 15 },
  timelineColumn: { width: '48%' },
  timelineDate: { fontSize: 12, fontWeight: '600', color: '#747D8C', marginBottom: 6, textAlign: 'center' },
  mockPhoto: { height: 140, borderRadius: 12, justifyContent: 'center', alignItems: 'center' },
  photoText: { textAlign: 'center', fontSize: 13, fontWeight: '600', color: '#4A5568', lineHeight: 18 },
  progressSummary: { backgroundColor: '#EDF2F7', padding: 16, borderRadius: 12, marginTop: 15 },
  summaryTitle: { fontSize: 14, fontWeight: '700', color: '#2B6CB0', marginBottom: 4 },
  summaryText: { fontSize: 13, color: '#4A5568', lineHeight: 18 },

  /* Bottom Nav Mechanics */
  bottomNav: { position: 'absolute', bottom: 0, left: 0, right: 0, height: 75, backgroundColor: '#FFF', flexDirection: 'row', borderTopWidth: 1, borderColor: '#E2E8F0', paddingBottom: 15 },
  navItem: { flex: 1, justifyContent: 'center', alignItems: 'center' },
  activeNavItem: { backgroundColor: '#F8F9FA' },
  navText: { fontSize: 12, color: '#A0AEC0', fontWeight: '500' },
  activeNavText: { color: '#6C5CE7', fontWeight: '700' }
});
